# actuarialsymbol for MathJax, 3.3

actuarialsymbol for MathJax is a 3rd-party extension for MathJax, for typesetting actuarial symbols.

## Usage and Key features

### Comprehensive life contingencies symbol list

- [List of implemented symbols and code to reproduce them](https://madev34.github.io/actuarialsymbol-MathJax/)


### Shortcuts for life table, insurance and annuity symbols

    \lx{}
    \Lx{}
    \dx{}
    \Dx{}
    \px{}
    \qx{}
    \eringx{}
    \Ax{}
    \ax{}
    \Ex{}
    \sx{}
    \aringx{}
    
    (...)

###  Shortcuts for premiums, reserves and paid-up insurance
    
    \Px{}
    \Vx{}
    \Wx{}
    \premium{}
    \reserve{}
    \paidup{}


### Shortcuts for auxiliary symbols
    
    \angl{}
    \endow{}{}
    \term{}{}
    \pureendow{}{}
    
    
### Shortcuts for varying benefit insurance and annuities

    \IA{}
    \DA{}
    \Ia{}
    \Da{}
    \Is{}
    \Ds{}
    
    (...)
 
### Shortcuts for precedence numbers

    \itop{}
    \iitop{}
    \iiitop{}
    
    \ibottom{}
    \iibottom{}
    \iiibottom{}



## Developpement
This project is still in developpement. The extension is not currently implemented in MathJax V3.3.

Upon completion, one could simply use *\require{actuarialsymbol}* in a Tex expression to load the extension. To add it to MathJax configuration bloc, one could simply add the following :

    window.MathJax = {
    loader: {load: ['[tex]/actuarialsymbol']},
    tex: {packages: {'[+]': ['actuarialsymbol']}}
    };


**References :**

- [LaTex package documentation](https://ctan.math.illinois.edu/macros/latex/contrib/actuarialsymbol/actuarialsymbol.pdf)
- [LaTex package repository](https://gitlab.com/vigou3/actuarialsymbol)
- [LaTex package home page](https://vigou3.gitlab.io/actuarialsymbol/)
- [MathJax-third-party-extensions on GitHub](https://github.com/mathjax/MathJax-third-party-extensions)
