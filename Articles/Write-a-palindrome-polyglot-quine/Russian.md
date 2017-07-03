[<img align="left" alt="PalidromePolyglotQuine" src="https://habrastorage.org/files/b0e/458/9ec/b0e4589ec6494616b28f63c65843d896.png"/>](https://habrahabr.ru/post/309702/)

Поздравляю всех трансляторов человеческого языка в машинный с их профессиональным днем, желаю вам меньше багов и больше-либо-равно классных идей! А в качестве идейного подарка со своей стороны предлагаю решение одной красивой задачи - написание кода, который на выходе выдаёт свой собственный текст, является валидным для интерпретаторов и компиляторов разных языков, и при этом правильно исполняется при реверсе исходников.

Не так давно я узнал о коде, который может одновременно интерпретироваться в PHP и компилироваться в Java: [PhpJava.java](https://gist.github.com/forairan/b1143f42883b3b0ee1237bc9bd0b7b2c). Как оказалось, эта идея не нова: код, валидный сразу для нескольких компиляторов или интерпретаторов, называется [полиглотом (polyglot)](https://en.wikipedia.org/wiki/Polyglot_(computing)). Такой код возможно писать из-за особенностей обработки строк и комментариев в различных интерпретаторах или компиляторах.<cut/>

<cut/>

Например, в Java можно описывать символы как в обычном виде, например символ '/', так и в виде юникод-записи: 'u002F'. В компиляторе C\# такие записи не будут валидными. Однако если их "спрятать" в комментарий, то, с одной стороны, они не будут мешать при компиляции C# кода, с другой — будут валидными в Java-коде. Например, если нужно, чтобы код **A** компилировался только в языке C#, но не компилировался в Java, а код **B** компилировался только в Java, но не компилировался в C#, нужно использовать следующий фрагмент:

```
//\u000A\u002F\u002A
A//\u002A\u002FB
```

C#-компилятор будет "воспринимать" этот код обычным образом, комментарии останутся комментариями:

```CSharp
//\u000A\u002F\u002A
A//\u002A\u002FB
```

А вот с Java все интересней, т.к. юникод-запись трасформируется и получится следующее:

```Java
//
/*
A//*/B
```

Комбинируя общие для обоих языков инструкции, а также разделяя различные, можно написать любую программу.

Однако такими юникод-записями трюки не ограничиваются. Например, в C-подобных языках существуют директивы препроцессора, которые могут определять, какой код должен компилироваться, а какой нет. В некомпилируемый код можно помещать код совсем другого языка. Например, ниже приведен код-полиглот на C++ и Python ([отсюда](https://gist.github.com/LionZXY/5916ce355d08d6d43a8b6acd71951c25)), в котором в секции `#if false` как раз и помещен код Python. А последовательности `'''` начинают и заканчивают комментарий в коде Python.

```C
#include <stdio.h>
#if false
print "Hello world"
'''
#endif
int main() {
printf("Hello world");
return 0;
}
#if false
'''
#endif
```

В HTML, например, комментарии начинаются с последовательности символов `<!--`, что также можно использовать. Есть и более сложные полиглоты, работающие одновременно на 6 и на 16 языках. Первый выводит сообщение "hitforum" для всех языков, а второй работает интересней: выводит название языка, на котором происходит его компиляция или интерпретация.

### Код-полиглот на C, Shell, Perl, Brainfuck, Befunge, Whitespace

```
# define x u    /*            v
#    :::::::::::::::::::>>>>>>>$$$a"muroftih"#[>:#,_@]
eval 'echo "hitforum";exit';sub echo { print    "@_\n"}               
__END__>++++++++++>++++++++++[>+++++++++++>++++++++++    
+<<-]>------.+.>++++++.<---.+++++++++.>--.+++                        
.<--.<<.    */
main() { printf ("hitforum\n"); }
```

<spoiler title="Код-полиглот на 16 язках">
```Perl
# /* [	<!-- */ include	<stdio.h> /* 	\
	#`{{coding=utf-8\
"true" if 0 != 0 and	q != """0"	;	`	\
	\
if [ -n "$ZSH_VERSION" ]; then		 		 	\
	\
    echo exec	echo I\'m a zsh script.; \
	\
elif [ -n "$BASH_VERSION" ]; then		    	\
	\
    echo exec	echo I\'m a bash script.; \
else	\
    echo exec	echo	I\'m	a sh	script.;		\
fi`;	#!;#\
BEGIN{print"I'm a ", 0 ? "Ruby"	:"Perl",	" program.\n";	exit; }  
	#\
%q~     		 	  	
	
set =dummy 0; puts [list "I'm"	"a"	"tcl"	"script."]; exit	  
	
all: ; @echo "I'm a Makefile."		  	 	\
	#*/
/*: */ enum {a, b}; 			  		\
	\
static int c99(void) {  			    
	
 #ifndef __cplusplus /* bah */		    	
	
unused1: if ((enum {b, a})0) 		   		\
	(void)0;
 #endif    		  	 	
	
unused2:    return a;	     \
}	\
static int trigraphs(void) {  			    \
	\
    return sizeof	"??!"	==	2;  	 \
}	\
char X;    		 				\
	\
int main(void) {   		  			\
	\
    struct X	{		  	 \
	\
     	char	a[2];    	\
	};\
    if (sizeof(X)	!=	1) {		 	\
	\
printf("I'm a C++ program (trigraphs %sabled).\n",	 			 \
	\
     trigraphs()	? "en"	: "dis");\
	\
}else if (1//**/2


)unused3 : { ; \
        printf("I'm a C program (C%s, trigraphs %sabled).\n", \
               c99() ? "89 with // comments" : "99", \
               trigraphs() ? "en" : "dis"); \
    } else { \
        printf("I'm a C program (C89, trigraphs %sabled).\n", \
               trigraphs() ? "en" : "dis"); \
    } \
    return 0; \
} /*
 # \
\begin{code}
import Prelude hiding ((:)); import Data.List (intercalate); import Language.Haskell.TH; import Data.String; default (S, String, Integer, Double); data S = S; instance Eq S where { _ == _ = False }; instance IsString S where { fromString = const S }; ifThenElse c t e = case c of True -> t; False -> e
cPP = False; {-
#define cPP True
-} main :: IO ()
main = putStr ("I'm a Literate Haskell program" ++ bonus ++ ".\n") where
  _ = (); bonus | null details = "" | otherwise = " (" ++ details ++ ")"
  details = intercalate ", " [ name | (True, name) <- extensions ] :: String
  extensions =
    (bangPatterns,              "BangPatterns"             ) :
    (templateHaskell,           "TemplateHaskell"          ) :
    (rebindableSyntax,          "RebindableSyntax"         ) :
    (magicHash,                 "MagicHash"                ) :
    (overloadedStrings,         "OverloadedStrings"        ) :
    (noMonomorphismRestriction, "NoMonomorphismRestriction") :
    (scopedTypeVariables,       "ScopedTypeVariables"      ) :
    (cPP,                       "CPP"                      ) :
    (unicodeSyntax,             "UnicodeSyntax"            ) :
    (negativeLiterals,          "NegativeLiterals"         ) :
    (binaryLiterals,            "BinaryLiterals"           ) :
    (numDecimals,               "NumDecimals"              ) : []
  (!) = (!!)
  bangPatterns = [True] ! 0 where foo !bar = False
  templateHaskell = thc $(return (TupE []) :: ExpQ)
  rebindableSyntax = null (do { [()]; [()] })
    where _ >> _ = [] :: [()]
  magicHash = foo# () where
    foo = ['.']; "." # _  = False; foo# _ = True
  overloadedStrings = "" /= ""
  noMonomorphismRestriction = show foo == "0" where
    foo = 0
    bar = foo :: Double
  unicodeSyntax = let (★) = True in (*) where
    (*) = False
  negativeLiterals = -1 == NNa
  binaryLiterals = let b1 = 1 in 0b1 == 1
  numDecimals = show 0e0 == "0"
  scopedTypeVariables = stv (0 :: Double) == "0.0"
data{- = -} NN = NNa | NNb deriving Eq; instance Num NN where { fromInteger _ = NNa; negate _ = NNb; _ + _ = NNa; _ * _ = NNa; abs _ = NNa; signum _ = NNa }
instance{- = -} (Num a) => Num (e -> a) where { fromInteger = const . fromInteger; negate = (.) negate; abs = (.) abs; signum = (.) signum; x + y = \e -> x e + y e; x * y = \e -> x e * y e }
class THC a where { thc :: a -> Bool }; instance THC () where { thc _ = True }; instance THC (Q a) where { thc _ = False }; class (Show a, Num a) => STV a where
  stv :: a -> String
  stv = const $ show (f 0) where
    f = id :: a -> a
instance STV Double -- : \
\end{code}

 # \
]>++++++++[<+++++++++>-]<+.>>++++[<++++++++++>-]<-.[-]>++++++++++ \
[<+++++++++++>-]<-.>>++++[<++++++++>-]<.>>++++++++++[<++++++++++> \
-]<- - -.<.>+.->>++++++++++[<+++++++++++>-]<++++.<.>>>++++++++++[ \
<++++++++++>-]<+++++.<<<<+.->>>>- - -.<+++.- - -<++.- ->>>>>+++++ \
+++++[<+++++++++++>-]<- - -.<<<<<.<+++.>>>.<<<-.- ->>>>+.<.<.<<.> \
++++++++++++++.[-]++++++++++""" else 0
 # \
from platform import * # \
print("I'm a Python program (%s %s)." % # [-][ \
(python_implementation(), python_version())); """--><html><head>
<!--:--><title>I'm a HTML page</title></head><body>
<!--:--><h1>I'm a <marquee><blink>horrible HTML</blink></marquee> page</h1>
<!--:--><script language="JavaScript">
<!--: # \
setTimeout( // \
   function () { // \
      document.body.innerHTML = "<h1>I'm a javascript-generated HTML page</h1>"; // \
   }, 10000); // \
//-->
</script><!--: \
</body></html><!-- }} # \
say "I'm a Perl6 program."; # """ # */
 #define FOO ]-->~
```
</spoiler>

## Квайн-полиглот

Для того чтобы написать квайн-полиглот на языках C# и Java, необходимо совместить принципы разработки квайна и полиглота. Как оказалось, и такая тема не нова: на сайте codegolf пользователи соревнуются, у кого квайн-полиглот или поликвайн получится короче: [Write a Polyquine](http://codegolf.stackexchange.com/questions/37464/write-a-polyquine). Однако в этом вопросе не было вариантов с более многословными языками C# и Java, что мне и захотелось исправить.

Для написания такого квайна-полиглота нужно экранировать символы, запрещенные в строках обоих языков и встречающиеся в строках самой программы. Такими символами являются кавычки ", перенос строки \n и обратный слеш \\. А чтобы еще уменьшить размер кода, повторяющиеся последовательности символов, такие как \\u000A, \\u002F и \\u002A, также были заменены на одиночные символы в самой кодирующей строке. Вот пример получившегося квайна-полиглота, валидного для компиляторов C# и Java:

### PolyglotQuine.cs.java, 757 символов:

```CSharp
//\u000A\u002F\u002A
using System;//\u002A\u002F
class Program{public static void//\u000A\u002F\u002A
Main//\u002A\u002Fmain
(String[]z){String s="//@#'^using System;//'#^class Program{public static void//@#'^Main//'#main^(String[]z){String s=!$!,t=s;int[]a=new int[]{33,94,38,64,35,39,36};String[]b=new String[]{!&!!,!&n!,!&&!,!&@!,!&#!,!&'!,s};for(int i=0;i<7;i++)t=t.//@#'^Replace//'#replace^(!!+(char)a[i],b[i]);//@#'^Console.Write//'#System.out.printf^(t);}}",t=s;int[]a=new int[]{33,94,38,64,35,39,36};String[]b=new String[]{"\"","\n","\\","\\u000A","\\u002F","\\u002A",s};for(int i=0;i<7;i++)t=t.//\u000A\u002F\u002A
Replace//\u002A\u002Freplace
(""+(char)a[i],b[i]);//\u000A\u002F\u002A
Console.Write//\u002A\u002FSystem.out.printf
(t);}}
```

## Квайн-полиглот-палиндром

Еще больше усложним задачу: попробуем написать квайн-полиглот-палиндром. Напомню, что палиндром — это число или текст, одинаково читающиеся в обоих направлениях. Принцип разработки квайнов-палиндромов я [описывал в статье](https://habrahabr.ru/post/189192/) 3 года назад, тоже в день программиста. Принцип кода-палиндрома заключается в том, что зеркальная часть программы помещается в однострочный или многострочный комментарий, что не мешает при компиляции. Простейший код-палиндром в C# выглядит следующим образом:

```CSharp
/**/class P{static void Main(){}};/*/;}}{)(niaM diov citats{P ssalc/**/
```

Как видим, многострочный комментарий `/*` начинается с середины и продолжается до конца, где и закрывается последовательностью `*/`. Пустой комментарий в начале нужен для того, чтобы строка полностью стала симметричной.

Итак, объединяя принципы создания палиндрома, полиглота и квайна, я написал следующий код:

### PalidromePolyglotQuine.cs.java, 1747 символов:

```CSharp
/**///\u000A\u002F\u002A
using System;//\u002A\u002F
class Program{public static void//\u000A\u002F\u002A
Main//\u002A\u002Fmain
(String[]z){String s="`**?`@#_^using System;?_#^class Program{public static void?@#_^Main?_#main^(String[]z){String s=!$!,t=s;int i;int[]a=new int[]{33,94,38,64,35,95,96,63,36};String[]b=new String[]{!&!!,!&n!,!&&!,!&@!,!&#!,!&_!,!`!,!?!,s};for(i=0;i<9;i++)t=t.?@#_^Replace?_#replace^(!!+(char)a[i],b[i]);t+='*';for(i=872;i>=0;i--)t=t+t?@#_^[i];Console.Write?_#.charAt(i);System.out.printf^(t);}}/",t=s;int i;int[]a=new int[]{33,94,38,64,35,95,96,63,36};String[]b=new String[]{"\"","\n","\\","\\u000A","\\u002F","\\u002A","/","//",s};for(i=0;i<9;i++)t=t.//\u000A\u002F\u002A
Replace//\u002A\u002Freplace
(""+(char)a[i],b[i]);t+='*';for(i=872;i>=0;i--)t=t+t//\u000A\u002F\u002A
[i];Console.Write//\u002A\u002F.charAt(i);System.out.printf
(t);}}/*/}};)t(
ftnirp.tuo.metsyS;)i(tArahc.F200u\A200u\//etirW.elosnoC;]i[
A200u\F200u\A000u\//t+t=t)--i;0=>i;278=i(rof;'*'=+t;)]i[b,]i[a)rahc(+""(
ecalperF200u\A200u\//ecalpeR
A200u\F200u\A000u\//.t=t)++i;9<i;0=i(rof;}s,"//","/","A200u\\","F200u\\","A000u\\","\\","n\",""\"{][gnirtS wen=b][gnirtS;}63,36,69,59,53,46,83,49,33{][tni wen=a][tni;i tni;s=t,"/}};)t(^ftnirp.tuo.metsyS;)i(tArahc.#_?etirW.elosnoC;]i[^_#@?t+t=t)--i;0=>i;278=i(rof;'*'=+t;)]i[b,]i[a)rahc(+!!(^ecalper#_?ecalpeR^_#@?.t=t)++i;9<i;0=i(rof;}s,!?!,!`!,!_&!,!#&!,!@&!,!&&!,!n&!,!!&!{][gnirtS wen=b][gnirtS;}63,36,69,59,53,46,83,49,33{][tni wen=a][tni;i tni;s=t,!$!=s gnirtS{)z][gnirtS(^niam#_?niaM^_#@?diov citats cilbup{margorP ssalc^#_?;metsyS gnisu^_#@`?**`"=s gnirtS{)z][gnirtS(
niamF200u\A200u\//niaM
A200u\F200u\A000u\//diov citats cilbup{margorP ssalc
F200u\A200u\//;metsyS gnisu
A200u\F200u\A000u\///**/
```

К сожалению, монстр получился слишком большим (1747 символов), однако это объясняется длинными цепочками юникод-символов и многословностью языков C# и Java. Уверен, что на других языках можно будет написать квайн-палиндром-полиглот гораздо меньшего размера.

Теперь проверим, как эта программа исполняется. Для начала избавимся от всех комментариев и правильно отформатируем код:

<spoiler title="Отформатированный и очищенный код PalidromePolyglotQuine.cs.java под C#">
```CSharp
using System;
class Program
{
    public static void Main(String[] z)
    {
        String s = "`**?`@#_^using System;?_#^class Program{public static void?@#_^Main?_#main^(String[]z){String s=!$!,t=s;int i;int[]a=new int[]{33,94,38,64,35,95,96,63,36};String[]b=new String[]{!&!!,!&n!,!&&!,!&@!,!&#!,!&_!,!`!,!?!,s};for(i=0;i<9;i++)t=t.?@#_^Replace?_#replace^(!!+(char)a[i],b[i]);t+='*';for(i=872;i>=0;i--)t=t+t?@#_^[i];Console.Write?_#.charAt(i);System.out.printf^(t);}}/",
            t = s;
        int i;
        int[] a = new int[] { 33, 94, 38, 64, 35, 95, 96, 63, 36 };
        String[] b = new String[] { "\"", "\n", "\\", "\\u000A", "\\u002F", "\\u002A", "/", "//", s };
        for (i = 0; i < 9; i++)
            t = t.Replace("" + (char)a[i], b[i]);
        t += '*';
        for (i = 872; i >= 0; i--)
            t = t + t[i];
        Console.Write(t);
    }
}
```
</spoiler>

Из листинга становится понятно, что переменная `s` содержит код программы, в котором экранированы запрещенные в строках символы и сжаты повторяющиеся последовательности. Ниже представлена таблица символов в формате код — символ — замена, которая используется для формирования выводимой строки `t`.

| код | символ | замена  |
|----|---|--------|
| 33 | ! | "      |
| 94 | ^ | \n     |
| 38 | & | \      |
| 64 | @ | \u000A |
| 35 | # | \u002F |
| 95 | _ | \u002A |
| 96 | ` | /      |
| 63 | ? | //     |
| 36 | $ | s      |

На следующем этапе происходит конкатенация строки `t` с ней же, инвертированной для того, чтобы на выходе получился палиндром. Стоит отметить, что число 872 (длина строки `t`) необходимо просчитывать после того, как квайн уже был написан. А для этого необходимо запускать уже написанный код, что также представляет определенные сложности.

Главным критерием при написании такого кода было достижение наименьшего размера в текстовом виде, а не его чистота. Поэтому, понятное дело, выглядит он несколько странно. 

Как видим, ничего сложного в написании таких квайнов нет. Для тех, кто не верит, что это  все действительно работает, были написаны тесты в репозитории [Freaky-Sources](https://github.com/KvanTTT/Freaky-Sources/blob/master/FreakySources.Tests/QuineTests.cs) (для запуска требуется, чтобы Java была установлена).

Кидайте в комментарии ваши квайнды-палиндромы-полиглоты на других языках и другие интересные кодофричные вещи, с удовольствием их изучу.

Еще раз поздравляю всех программистов и сочувствующих!