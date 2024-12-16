# MyWay+
WCAG failures for the MyWay+ digital ticketing platform
All WCAG testing follows the WCAG-EM audit methodology testing. Issues are categorised by the severity level to describe likely user impact

* **Severity 4 Low** - Unlikely to prevent anyone from accessing content but could be a minor problem.
* **Severity 3 Medium** - Could make accessing and navigating content difficult for some people.
* **Severity 2 High** - This will present significant access issues, but workarounds are available
* **Severity 1 Critical** - Will prevent the flow from being completed. Requires third-party assistance as there is no path to work around the issue.

## Login - [https://www.mywayplus.transport.act.gov.au/login](https://www.mywayplus.transport.act.gov.au/login) n/a
| Issue  | Element | WCAG Criterion  | WCAG Level  | Severity  |
|:---|:---|:---|:---:|---|
| Poor colour contrast on Quick Top Up and Buy a QR Ticket  | - | [1.4.3 Contrast (Minimum)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)  | AA  | High  |
| Unlabelled form controls | - | [1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/Understanding/info-and-relationships.html)  | A  | High  |
| Unreachable page links  | - | [2.1.1 Keyboard](https://www.w3.org/WAI/WCAG21/Understanding/keyboard.html)  | A  | Critical  |

## Sign Up - [https://www.mywayplus.transport.act.gov.au/signup](https://www.mywayplus.transport.act.gov.au/signup)
| Issue  |  Element | WCAG Criterion  | WCAG Level  | Severity  |
|:---|:---|:---|:---:|---|
| Unlabelled terms of service checkbox  |- | [1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/Understanding/info-and-relationships.html)  | A  | High  |
| No focus indicator on terms of service checkbox  |- | [2.4.7 Focus Visible](https://www.w3.org/WAI/WCAG21/Understanding/focus-visible.html)  | AA  | High  |
| Poor colour contrast on all form elements `placeholder` text  |- | [1.4.3 Contrast (Minimum)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)  | AA  | High  |
| Colour only focus indicator on Mobile No. select control  |- | [1.4.1 Use of Color](https://www.w3.org/WAI/WCAG21/Understanding/use-of-color.html)  | A  | Medium  |
| Unlabelled back button on Quick Top Up dialog  |- | [1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/Understanding/info-and-relationships.html)  | A  | High  |
| User edittable controls First Name, Last Name, Password, Email missing `autocomplete` attribute |- | [1.3.5 Identify Input Purpose](https://www.w3.org/WAI/WCAG21/Understanding/identify-input-purpose.html)  | AA  | Low  |
| No focus indicator on Are you sure dialog |- | [2.4.7 Focus Visible](https://www.w3.org/WAI/WCAG21/Understanding/focus-visible.html)  | AA  | High  |
| Are you sure dialog missing `dialog` role |- | [4.1.2 Name Role Value](https://www.w3.org/WAI/WCAG21/Understanding/name-role-value.html)  | A  | High  |

