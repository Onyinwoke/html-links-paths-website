# Assignment 2.4 — Links, Paths and a Multi-Page Website

## Link and Path Table

| Link text | Destination | Type | Why it works |
|---|---|---|---|
| Home | `index.html` | Relative | Opens the homepage from the website's root folder. |
| About | `about.html` | Relative | Opens `about.html` in the same folder. |
| Services | `pages/services.html` | Relative | Opens the Services page inside the `pages` folder. |
| Projects | `projects.html` | Relative | Opens `projects.html` in the same folder. |
| Contact | `contact.html` | Relative | Opens `contact.html` in the same folder. |
| Home from Services | `../index.html` | Relative | Goes up one folder from `pages` to reach the homepage. |
| About from Services | `../about.html` | Relative | Goes up one folder to reach the About page. |
| Services from Services | `services.html` | Relative | Opens the current Services page from within `pages`. |
| Projects from Services | `../projects.html` | Relative | Goes up one folder to reach the Projects page. |
| Contact from Services | `../contact.html` | Relative | Goes up one folder to reach the Contact page. |
| Learn more about this website | `#learn-more` | Fragment | Jumps to the section with `id="learn-more"` on the same page. |
| HTML on MDN Web Docs | `https://developer.mozilla.org/en-US/docs/Web/HTML` | Absolute HTTPS URL | Opens an external website using a complete HTTPS address. |
| Send me an email | `mailto:onyinyenwoke@gmail.com` | Email link | Opens the user's default email application with the recipient address filled in. |

## Testing

I tested the website navigation in the browser. The links opened their intended pages, including the link from the homepage to Services and the return link from Services to Home.
