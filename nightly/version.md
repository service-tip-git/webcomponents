commit 9ca0ef0c4333c22a9e43c86d87c31e4a35f61e3f
Author: ilhan007 <ilhan.myumyun@sap.com>
Date:   Fri Jul 3 11:40:16 2026 +0300

    test(ui5-dialog): use i18n bundle default text for aria-describedby assertions
    
    The Dialog.cy.tsx test hardcoded the English strings for the aria-describedby
    hidden text. After the translation delivery renamed the i18n keys, use the
    i18n bundle default text so the assertions stay in sync with the source.
