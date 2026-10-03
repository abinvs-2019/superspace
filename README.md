# SuperSpace

Marketing landing page for SuperSpace — a mobile app for live 1:1 video & voice
consultations with verified experts and advisors. Two-sided marketplace:
seekers find and pay experts per minute; experts earn and withdraw revenue.
India-first (₹ pricing, UPI).

Single self-contained `index.html` (Tailwind CDN, no build step). Open directly
or serve via GitHub Pages.

## Pages

GitHub Pages serves each `.html` file without its extension.

| URL | File |
|---|---|
| `/` | `index.html`: the landing page |
| `/terms` | `terms.html`: Terms of Service |
| `/privacy-policy` | `privacy-policy.html`: Privacy Policy |
| `/refund-policy` | `refund-policy.html`: Refund Policy |
| `/safety-standards` | `safety-standards.html`: CSAE standards |
| `/contact` | `contact.html`: support, safety and grievance contact |

The legal pages share `assets/legal.css`. The Terms and Privacy Policy used to be
sections of `index.html`; a script there sends old `/#terms` and `/#privacy`
links to the new pages.
