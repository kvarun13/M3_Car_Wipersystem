<html>
<body>
<!--StartFragment--><h1 dir="auto" style="box-sizing: border-box; font-size: 2em; margin-top: 0px !important; margin-right: 0px; margin-bottom: 16px; margin-left: 0px; font-weight: 600; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid var(--color-border-muted); color: rgb(36, 41, 47); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;">TEST CASES and Corresponding Output</h1><h2 dir="auto" style="box-sizing: border-box; margin-top: 24px; margin-bottom: 16px; font-size: 1.5em; font-weight: 600; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid var(--color-border-muted); color: rgb(36, 41, 47); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><a id="user-content-high-level-test-cases" class="anchor" aria-hidden="true" href="https://github.com/MohanBabuS/M3_Control_Of_Wiper_System/tree/main/4_TestCase#high-level-test-cases" style="box-sizing: border-box; background-color: transparent; color: var(--color-accent-fg); text-decoration: none; transition: color 80ms cubic-bezier(0.33, 1, 0.68, 1) 0s, background-color, box-shadow, border-color; float: left; padding-right: 4px; margin-left: -20px; line-height: 1;"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>High Level Test Cases</h2>

Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS
-- | -- | -- | -- | -- | --
1 | check if the BUTTTON is pressed | program execution | Microcontroller/Engine starts | LED ON(RED) | PASS
2 | check if the BUTTTON is pressed | program execution | WIPER starts | LED ON(BLUE) | PASS
3 | check if the BUTTTON is pressed | program execution | WIPER starts | LED ON(GREEN) | PASS
4 | check if the BUTTTON is pressed | program execution | WIPER starts | LED ON(ORANGE) | PASS
5 | check if the BUTTTON is pressed | - | Microcontroller/Engine stops | LED TURNED OFF | PASS

<br class="Apple-interchange-newline"><!--EndFragment-->
</body>
</html>


<html>
<body>
<!--StartFragment--><h2 dir="auto" style="box-sizing: border-box; margin-top: 24px; margin-bottom: 16px; font-size: 1.5em; font-weight: 600; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid var(--color-border-muted); color: rgb(36, 41, 47); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;">Low Level Test Cases</h2>

Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS
-- | -- | -- | -- | -- | --
1 | check if the BUTTTON is pressed | program execution | Microcontroller/Engine starts | LED ON(RED) | PASS
2 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is slow | LED ON(BLUE) | PASS
3 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is moderate | LED ON(GREEN) | PASS
4 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is good | LED ON(ORANGE) | PASS
5 | check if the BUTTTON is pressed again | - | Microcontroller/Engine stops | LED TURNED OFF | PASS

<br class="Apple-interchange-newline"><!--EndFragment-->
</body>
</html>
