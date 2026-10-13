# SuperSpace

Website for SuperSpace, the dating app where you say hi with a flower. Static HTML and one
stylesheet (`assets/site.css`), no build step. GitHub Pages serves it at
superspace.superbits.in and serves each `.html` file without its extension.

## Pages

| URL | File |
|---|---|
| `/` | `index.html`: the landing page |
| `/terms` | `terms.html`: Terms of Service |
| `/privacy-policy` | `privacy-policy.html`: Privacy Policy |
| `/refund-policy` | `refund-policy.html`: Refunds & Cancellations |
| `/community-guidelines` | `community-guidelines.html`: Community Guidelines |
| `/safety-tips` | `safety-tips.html`: dating safety tips |
| `/safety-standards` | `safety-standards.html`: Child Safety (CSAE) Standards |
| `/contact` | `contact.html`: help, safety reports and Grievance Officer |
| (any missing page) | `404.html` |

Keep these URLs: the app stores and the app itself link to them. The Terms keep their old
`#t-…` anchors, and a script on the home page sends old `/#terms`, `/#t-…` and `/#privacy`
links to the right page.

Every page shares the same header, footer and styles, so change them on every page
together. The legal pages must describe what the app actually does; update them when the
app changes, and change the "last updated" date.
