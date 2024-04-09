I'm thinking that I should go about the project like this:

1. Typography CSS file for setting the **responsive** styling for fonts, lettering etc

2. There should be a utility CSS file that contains all of the utility classes seperately from the other CSS files. I am unsure if this means that I will end up not making use of BEM **Modifiers**, eitherway I should refer to **https://css-tricks.com/building-a-scalable-css-architecture-with-bem-and-utility-classes/**

3. Project Code Structure: BEM, SCSS & Utility Classes

    3.1 References
        3.1.1 - **https://css-tricks.com/building-a-scalable-css-architecture-with-bem-and-utility-classes/**
        3.1.2 - **https://cssguidelin.es/#bem-like-naming** - This isn't really taken into consideration as I currently write this document but I would assume it could come in handy a handful of times
        3.1.3 - **https://github.com/kneath/kss/blob/master/SPEC.md** - This is only for understanding how the CSS styling will be "organized", well that is worded poorly but yeh. Once again, I do not intend of focusing much if it all on this but I plan to make use of the **"Styleguide"** mentioned at the end of the linked GitHub file

    3.2 Tools
        3.2.1 **BEM Helper** VS Code extension 
        3.2.2 **SCSS BEM Support** VS Code extension

**My Workflow:**

1. Write the a single section in HTML following the BEM naming convention & nesting structure (avoid deep nesting)
2. Generate a BEM compatible SCSS file for the highlighted HTML section in question by using the **">Generate Stylsheet from selection"** command set by the **BEM Helper** VS extension.
    Note: Bare in mind that the created scss file will not appear in the folder explorer until you manually save that specific scss file

