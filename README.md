[![Netlify Status](https://api.netlify.com/api/v1/badges/e9f18550-656f-443f-b4c4-bfa53ae9684e/deploy-status)](https://app.netlify.com/projects/ajsyslog/deploys)


# 🧠 AJ's SysLog — A Personal Tech Blog

Welcome to **AJ's SysLog**, my personal tech blog focused on cybersecurity, systems thinking, software development, and the journey of lifelong learning in tech.

This site is built using the [Jekyll](https://jekyllrb.com/) static site generator and the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme. It's deployed using [Netlify](https://www.netlify.com/) and powered by [Netlify CMS](https://www.netlifycms.org/) for easy content management.

---

## 📂 Repo Structure

- `_posts/` – Blog posts written in Markdown
- `_data/` – Configuration files for menus, social links, etc.
- `contact.md` – Contact page (email, GitHub, LinkedIn)
- `admin/` – Netlify CMS configuration
- `_config.yml` – Main Jekyll configuration
- `assets/` – Static assets (images, styles, etc.)

---

## ✍️ Content Management (Netlify CMS)

Netlify CMS allows editing and creating blog posts through a web interface.

🔗 Access:  
`https://ajsyslog.netlify.app/admin`

🧑‍🚀 Setup includes:
- Git Gateway auth
- Posts saved to `_posts/`
- Image uploads to `assets/images`

---

## 🔁 Branch Workflow

| Branch       | Purpose                        |
|--------------|--------------------------------|
| `production` | Live version of the site       |
| `development`| Actively edited version        |
| `backup`     | Automated backups   |

> Changes are made in `development`, reviewed, then merged to `production`.

---

## 📬 Contact

Find me on:
- GitHub: [github.com/ajwint-cs](https://github.com/ajwint-cs)
- LinkedIn: [linkedin.com/in/aj-in-cs](https://linkedin.com/in/aj-in-cs)
- Email: [ajs.syslog@gmail.com](mailto:ajs.syslog@gmail.com)

---

## 🛠️ Local Development

To run this site locally:

```bash
bundle install
bundle exec jekyll serve
```
Then visit:
http://localhost:4000


## License
This work is published under [MIT][mit] License.

## 🙌 Acknowledgments
Chirpy Jekyll Theme
Jekyll
Netlify
Netlify CMS
