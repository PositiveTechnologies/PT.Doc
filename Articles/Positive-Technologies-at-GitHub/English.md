# Positive Technologies on GitHub

![Positive Technologies ❤ GitHub](PT-love-GitHub-780-300.jpg)

Currently, an increasing number of companies, such as Google, Microsoft,
Facebook, and JetBrains, are placing in open access the code of both
small and big projects. Positive Technologies is famous not only for its
skilled professionals in IT security but also for a lot of professional
developers. This enables us to make a contribution into further
development of the Open Source project.

PT has the following GitHub groups that support our open projects:

* [Positive Technologies](https://github.com/PositiveTechnologies)
* [Open DevOps Community](https://github.com/devopshq)
* [Positive Research](https://github.com/ptresearch)
* [Positive JS](https://github.com/positive-js)
* [LibProtection](https://github.com/LibProtection/)

We have given a detailed description of the first group together with its
projects and a brief description of others.

## Contents

* [Organizations](#groups)
  * [Positive Technologies](#positive-technologies)
  * [Open DevOps Community](#open-devops-community)
  * [Positive Research](#positive-research)
  * [Positive JS](#positive-js)
  * [LibProtection](#libprotection)
* [Projects](#projects)
  * [PT.PM](#ptpm)
  * [ANTLR grammars](#antlr-grammars)
  * [PT.SourceStats](#ptsourcestats)
  * [AspxParser](#aspxparser)
  * [FP Community Rules](#fp-community-rules)
  * [Education and demo projects](#education-and-demo-projects)
* [License](#license)
* [Conclusion](#conclusion)

## Groups

### Positive Technologies

This is the main group where we develop projects designed for open
access from the start and those that used to be exclusively insider
projects. Education and demo projects are also run here.

### Open DevOps community

<img align="left" src="OpDevOps.png" alt="Open DevOps Community" hspace=15 />

The Community is aimed to build ready-made open solutions for managing
the full cycle of development, testing, and related processes, as well
as product delivery, deployment, and licensing.

Currently, the Community is at an early stage of development but it
already provides some useful Python-based tools. Yes, we do love Python!

Active projects:

1. [**Crosspm**](https://github.com/devopshq/crosspm) is a universal
   package manager enabling to download packages to assemble
   multi-component products on the basis of rules set out in the
   manifest.
2. [**Vspheretools**](https://github.com/devopshq/vspheretools) is a
   tool that allows to control vSphere machines straight from the
   console. It is also possible to use it as an API library in your
   Python scripts.
3. [**YouTrack Python 3 Client
   Library**](https://github.com/devopshq/youtrack) is a Python client
   to work with API YouTrack.
4. [**TFS API Python client**](https://github.com/devopshq/tfs) is
   Python client to work with API Team Foundation Server by Microsoft.
5. [**A Python client for
   Artifactory**](https://github.com/devopshq/artifactory) is a Python
   client to work with the Artifactory API binary data storage.
6. [**FuzzyClassificator**](https://github.com/devopshq/FuzzyClassificator)
   is a universal [neuro-fuzzy
   classifier](http://math-n-algo.blogspot.ru/2014/08/FuzzyClassificator.html)
   of arbitrary objects whose properties can be measured based on a
   fuzzy scale.

Each tool has an automatic Travis Cl build uploadable to the PyPi
repository where it can be found and installed with the standard pip
install.

Some other tools are getting ready to be published:

1. **CrossBuilder** is a system for cross-platform builds (build as a
   code). It is just like Travis CI while being independent of a Cl
   system used (TeamCity, Jenkins, GitLab-CI, etc.).
2. **ChangelogBuilder** generates release notes describing any
   amendments made to product features. This generator receives and
   aggregates data from various trackers (TFS, YouTrack, GitLab, etc.).
3. **polyglot.sketchplugin** is a plugin for the Sketch system used by
   designers for easier handling of multilingual text composition.

Everybody is welcome to contribute a new tool. If you wish to create
your own project, please see our
[ExampleProject](https://github.com/devopshq/ExampleProject) for the
project structure and detailed guidelines on how to create a project.
All you need to do is to copy it and create your own project on the
basis of ExampleProject. If you do have any ideas or tools for
automation, you are welcome to share them with the Community under an
MIT license. This is fashionable, honorable and prestigious :)

### Positive research

This is a repository for publishing research articles, presentations,
utilities (including those for detecting vulnerabilities), signatures,
and methods of attack detection.

* [**Pentest-Detections**](https://github.com/ptresearch/Pentest-Detections)
  is a utility that enables quick network scanning (with support of
  IPv4 and IPv6) and detection of vulnerabilities that can be
  exploited by WannaCry or NotPetya.
* [**UnME11**](https://github.com/ptresearch/unME11) are tools that
  allow to decode the latest versions of Intel ME 11.x.
* [**Bad_Tuesday_Cryptor_SIEM**](https://github.com/ptresearch/Bad_Tuesday_Cryptor_SIEM)
  is a MaxPatrol SIEM package for combatting of NotPetya.
* [**Me-disablement**](https://github.com/ptresearch/me-disablement)
  are methods to disable Intel ME. The repository contains only the
  old method. For a new method on the basis of High Assurance Platform
  (HAP), please see our article [*Disabling Intel ME 11 via undocumented mode*](http://blog.ptsecurity.com/2017/08/disabling-intel-me.html).

#### [AttackDetection](https://github.com/ptresearch/AttackDetection)

The attack team provides to this repository some rules for vulnerability
exploitation thanks to the intrusion detection systems
[Snort](https://www.snort.org/) и [Suricata IDS](https://suricata-ids.org/).
The project's main goal is to create
rules for vulnerabilities that are widely spread and have high severity.
The repository contains files for integration with
[oinkmaster](http://oinkmaster.sourceforge.net/), a script for updating
and deploying rules in a designated IDS. The repository also has traffic
files to test the rules. Notably, the repository has been added to
favorites 100 times while about 40 new vulnerabilities have been
discovered for the year, including BadTunnel, ETERNALBLUE, ImageTragick,
EPICBANANA, and SambaCry. Announcements about new vulnerabilities are
published in [Twitter](https://twitter.com/attackdetection).

### Positive JS

This is a community for developing tools (mainly web tools) used in PT
products.

### LibProtection

This is an organization uniting Positive Development User Group's
members who are currently working on adjusting the LibProtection library
for various languages and platforms. The library provides developers
with safe solutions for working with strings while perfectly ensuring
sanitization of input data and automated protection of applications from
injection attacks.

## Projects

### [PT.PM](https://github.com/PositiveTechnologies/PT.PM)

<img align="left" src="PT.PM-Logo-96.png" alt="PT.PM Logo" hspace=15 />

**PT Pattern Matching Engine** is a universal signature code analysis
that accepts user patterns written in a domain specific language (DSL). This
engine is used to check web applications for vulnerabilities contained
in [**Approof**](https://approof.ptsecurity.ru/), as well as in the source code
analyzer [**PT Application Inspector**](https://www.ptsecurity.com/ww-en/products/ai/).

The analysis includes several stages:

1. Parsing of the source code into the parse tree.
2. Converting the tree into a unified format.
3. Comparing the tree with user patterns.

The approach used in this project allows to unify the task of universal pattern
development for different languages.

PT.PM is conducting continuous integration, supporting assembly and
testing of modules both in Windows and in Linux (Mono). The development
is implemented via labelled issues and pull requests. Alongside with the
development, we also
[document](https://github.com/PositiveTechnologies/PT.PM/wiki) the
project while publishing results of all major builds both in the format
of [NuGet packages](https://www.nuget.org/packages/PT.PM/) and raw
[artifacts](https://ci.appveyor.com/project/KvanTTT/pt-pm/build/artifacts).
The way PT.PM is organized may be considered as an example for all further projects.

For the first stage, that is for source code parsing, we use parsers
based on ANTLR. The tool generates them for different *runtimes* on the
basis of formal grammars contained in the repository. Our company is
actively developing the repository. Currently, Java, C\#, Python 2 and
3, JavaScript, C++, Go, and Swift runtimes are supported while support for the
latter three has started just recently.

Noteworthy, ANTLR is used not only in PT projects on Application
Security but also in
[**Max Patrol SIEM**](https://www.ptsecurity.com/ru-ru/products/mpsiem/) where it
is used for processing the Domain Specific Language, which is applied for
description of dynamic asset groups. Knowledge exchange has prevented
waste of time on tasks already solved before.

### [ANTLR grammars](https://github.com/antlr/grammars-v4)

Positive Technologies has helped to develop and improve grammars for
PL/SQL, T-SQL, MySQL, PHP, Java 8, JavaScript, and C#.

#### [PL/SQL](https://github.com/antlr/grammars-v4/tree/master/plsql)

SQL grammar has vast syntax with lots of keywords. Fortunately, the
PL/SQL grammar already existed for ANTLR 3 and it was not that difficult
to port it for ANTLR 4.

#### [T-SQL](https://github.com/antlr/grammars-v4/tree/master/tsql)

No reliable parsers were found for T-SQL, not even mentioning open
sources, so it took us quite a long time and efforts to restore the
grammar on the basis of MSDN documents. Anyway, we finally managed to
achieve a great result: the grammar covers many common syntactic
constructions, looks neat, stays independent of the runtime, and it has
been tested (see the examples of SQL queries on MSDN). Since 2015, over
15 external users have contributed to the grammar. Moreover, the grammar
is also used now in **DBFW**, a prototype of network firewall for data
base management, the subproject of [**PT Application
Firewall**](https://www.ptsecurity.com/ww-en/products/af/).

#### [MySQL](https://github.com/antlr/grammars-v4/tree/master/mysql)

The grammar was developed by the team mentioned above on the basis of
T-SQL. It is also used in DBFW.

#### [PHP](https://github.com/antlr/grammars-v4/tree/master/php)

This grammar was translated from Bison to ANTLR. It is interesting for
its support of PHP, JavaScript, and HTML at once. To be more precise,
code sections of JavaScript and HTML are parsed into text, which is then
processed by parsers specifically for these languages.

#### [Java](https://github.com/antlr/grammars-v4/tree/master/java)

The grammar supporting Java 8 has been developed just recently. It is
based on grammar of the former version Java 7. The new grammar
introduces substantially expanded and improved test examples with
various syntaxes (AllInOne7.java, AllInOne8.java) and performance test
results for popular Java projects (including jdk8, Spring Framework,
Elasticsearch).

#### [JavaScript](https://github.com/antlr/grammars-v4/tree/master/javascript)

It was developed on the basis of the old grammar
[ECMAScript](https://github.com/antlr/grammars-v4/tree/master/ecmascript)
without strict compliance with the standard. When developing grammars,
we are primarily focused on practicality and simplicity and not just
formal compliance. Another distinctive feature is almost full support of
ECMAScript 6 as well as outdated constructions (HTML comments, CDATA
sections).

Not all syntax constructions can be described with grammar rules only.
In some cases, it is convenient and important to use the code on a
target runtime language. For instance, in JavaScript the token `get` is
just an identifier in some cases while in other cases it can be a
keyword describing a property getter. So, it is possible to parse this
token as a common identifier and check token values in the parser when
processing the property:

```ANTLR
getter
    : Identifier{p("get")}? propertyName
    ;
```

This grammar is interesting because these code fragments are
*universal* at least for C\# and Java runtimes thanks to the
[superClass](https://github.com/antlr/antlr4/blob/master/doc/options.md)
option.

This means that, in the C\# code, the function `p("get")` is
described in the parent class JavaScriptBaseParser.cs:

```CSharp
protected bool p(string str) =>  _input.Lt(-1).Text.Equals(str).
```

As for Java, this function looks as follows (JavaScriptBaseLexer.java):

```Java
protected boolean p(String str) {
    return _input.LT(-1).getText().equals(str);
}
```

#### [C\#](https://github.com/antlr/grammars-v4/tree/master/csharp)

Being mostly experimental, this grammar was created to compare the speed
of ANTLR and Roslyn parsers.

#### Developments and prospects

<img align="left" src="ANTLR-Logo-96.png" alt="ANTLR Logo" hspace=15 />

For more details on grammar development, please see our last year\'s
article [*Theory and Practice of Source Code Parsing with ANTLR and
Roslyn*](http://blog.ptsecurity.com/2016/06/theory-and-practice-of-source-code.html).

As can be seen in the change history and numerous number of merged pull requests
([tsql](https://github.com/antlr/grammars-v4/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Amerged+label%3Atsql+),
[plsql](https://github.com/antlr/grammars-v4/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Amerged+label%3Aplsql+),
[mysql](https://github.com/antlr/grammars-v4/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Amerged+label%3Amysql+)),
these grammars are constantly being improved not only by Positive Technologies
but also by a number of third-party developers. For the time of collaboration,
the repository has grown not only in terms of quantity but also in terms of quality.

### [PT.SourceStats](https://github.com/PositiveTechnologies/PT.SourceStats)

It allows to collect statistics for projects based on different
programming languages while being used in the free product Approof.

### [AspxParser](https://github.com/PositiveTechnologies/AspxParser)

This project is devoted to developing a parser of ASPX pages that is
used not only in the open PT.PM engine but also in the internal analyzer
of NET applications (**AI.Net**), which is based on abstract
interpretation of code.

### [FP Community rules](https://github.com/PositiveTechnologies/FP-community-rules)

<img align="left" src="Approof-Logo-96.png" alt="Approof Logo" hspace=15 />

In the repository, we are currently developing rule sets in the [YARA
format](http://yara.readthedocs.io/en/v3.4.0/writingrules.html). These
rule sets are used in the signature analysis module of Approof projects named
**FingerPrint**.

The FingerPrint engine is launched based on a set of source codes
(backend and frontend). In accordance with the rules described, YARA
searches for known versions of external components (for example, a
version 3 bla-bla library). The rules are set in such a way that they
contain signatures of vulnerable library versions where problems are
described in the text format.

Each rule includes several conditions for file checking. For instance,
that could be certain strings contained in a file. If the file meets the
conditions, Approof provides in the final report the information about
vulnerabilities found in a certain component, indicating the N version
and describing all related CVEs.

### Education and demo projects

At PHDays VII, the *Appsec Outback* master class was conducted at the
PDUG section. For the master class, we developed education and demo
versions of the [Mantaray static code
analyzer](https://github.com/PositiveTechnologies/mantaray) and [the
Schockfish network
firewall](https://github.com/PositiveTechnologies/shockfish). These
projects have all the main mechanisms that are used in mature security
tools. Unlike the latter, their main goal is to demonstrate algorithms
and security methods, help to understand the process of app analysis and
protection, and to show fundamental possibilities and limitations of
technologies.

The repository also contains examples of security tools implementation:

* [DOMSanitizer](https://github.com/PositiveTechnologies/DOMSanitizer/)
  — a module for detecting XSS attacks against web browsers
* [DOMParanoid](https://github.com/PositiveTechnologies/DOMParanoid/)
  — a module (security linter) for assessing HTML security.

## License

Our projects use both permission licenses (MIT, Apache) and our own, which
allows free non-commercial use.

## Conclusion

Our move to GitHub has proved to be quite useful and made us experienced
in various areas — setting up DevOps for Windows and Linux, document
writing, and developments.

Positive Technologies plans to expand Open Source projects even further.
