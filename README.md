# React-Refactorings

## Introduction 

Refactoring is a well-known technique to improve software quality. However, there are still relevant domains where refactoring has not been studied in-depth, such as JavaScript front-end frameworks. Essentially, such frameworks provide abstractions—called components—for structuring and organizing the codebase of modern and responsive Web UIs. Since these UIs can reach hundreds of components, it is natural to expect that suboptimal design decisions will eventually occur in their development. Therefore, information and documentation on the refactorings performed in these components have a practical value for practitioners nowadays, particularly for front-end developers.

To fill this gap, we empirically study refactorings that developers perform when maintaining and evolving *React*-based Web applications. By manually inspecting 171 refactoring commits performed in open source projects, we catalog 45 distinct refactoring operations of which 15 are specific to *React* code, nine are adaptations of traditional refactorings for the *React* context, 16 are traditional refactorings, and five are specific to JavaScript code. The catalog of refactorings proposed in this article migth support practitioners when improving the maintainability of *React* applications.

Please feel free to make pull requests and suggestions ([Issues][Issues] tab). We want to hear from you!

## Catalog of *React* Refactorings

In the following sections, we discuss the most frequent refactorings that developers perform when maintaining and evolving *React*-based Web applications. To ease their presentation and understanding, we classified these refactoring instances into four major categories: 

* *React*-specific refactorings, which are novel refactorings that only occur in front-end code that uses *React*.

* *React*-adapted refactorings, which are refactorings that although related to the *React* context can be seen as adaptations of traditional refactorings. 

* Traditional refactorings, i.e., refactorings documented in Fowler’s catalog).

* JavaScript-specific refactorings, which  are refactorings related to JavaScript code and structures and that were not previously classified as *React*-specific or *React*-adapted refactorings.

The following table summarizes the number of distinct refactoring operations we found by category and the number of occurrences.

Category | Number of Refactorings | Occurrences
| :--- | :---: | :---:
*React*-specific refactorings  | 15 | 51
*React*-adapted refactorings  | 9 | 97
Traditional refactorings  | 16 | 74
JavaScript-specific refactorings  | 5 | 10

### *React*-specific Refactorings

## About

This catalog was proposed by Fabio Ferreira and Marco Tulio Valente, from [ASERG/DCC/UFMG][ASERG].

Please feel free to make pull requests and suggestions ([Issues][Issues] tab).

<!-- Links -->
[React]: https://reactjs.org
[Facebook]: https://github.com/facebook
[ASERG]: http://aserg.labsoft.dcc.ufmg.br/
[Issues]: https://github.com/fabiosferreira/React-Code-Smells/issues
[eslint-plugin-react]: https://github.com/yannickcr/eslint-plugin-react
