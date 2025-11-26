# [BADGE] Github Repository Stats

[![Node JS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express JS](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](http://perso.crans.org/besson/LICENSE.html)
[![Open Source? Yes!](https://img.shields.io/badge/Open_Source%3F-Yes!-blue?style=for-the-badge&logo=gitHub&logoColor=white)](https://opensource.com/resources/what-open-source/)
![Language](https://img.shields.io/github/languages/top/dusk196/github-repo-stats?style=for-the-badge)
![Size](https://img.shields.io/github/languages/code-size/dusk196/github-repo-stats?style=for-the-badge)

So I was updating my Github with badges as per the latest trends. 😜 Then I noticed that there were no such badges to show the total number of contributions and total number of commit. I mean, sure there were a lot stats related badges like weekly commits or so but not this. So...

### A simple badge for GitHub Repositories that shows total number of contributions since it's inception!

Bdw, I was feeling pretty lazy to write all the SVGs myself and there were a ton of them already available so I just used the awesome hackable SVG badges from **Shields IO** (https://shields.io/).

Huge shoutout to the Devs! (https://github.com/badges/shields)

## Demo:

![Contributions](https://github-stats-badge.vercel.app/github/contrib/dusk196/github-repo-stats?style=for-the-badge&color=7678ed)
![Total Commits](https://github-stats-badge.vercel.app/github/commit/dusk196/github-repo-stats?style=for-the-badge&color=7678ed)

## How to use:

Well, it's pretty straight forward. You can use the following code in your Github Markdown file:
```markdown
![Github Badge](https://github-stats-badge.vercel.app/github/{type}/{username}/{repository_name})
```

You can also use the following HTML code should that be your choice for updaing the Github Markdown file.
```html
<img src="https://github-stats-badge.vercel.app/github/{type}/{username}/{repository_name}" />
```

### Request Parameters:

Parameter | Description
--- | ---
**type** | Defines the type of status you want. <br /> `contrib` (for contributions) \| `commit` (for total commits)
**username** | The Github username of the owner of the repository whose information status you require.  <br /> E.g: `dusk196`
**repository_name** | The Github repository name whose information status you require. <br /> E.g: `github-repo-stats`

**Example:**
```markdown
https://github-stats-badge.vercel.app/github/contrib/dusk196/github-repo-stats
```

### Query Parameters:

Since, it is based on **Shields IO** (https://shields.io/), it supports some of it's query parameters as follows:

Parameter | Description
--- | ---
**style** | Defines the style of badge you want. <br /> `plastic` \| `flat` \| `flat-square` \| `for-the-badge` \| `social`
**color** | The color of the badge; supports plaintext as well as hexcode <br /> E.g: `red` \| `green` \| `2f52e0` \| `7678ed` etc.

**Example:**
```markdown
https://github-stats-badge.vercel.app/github/contrib/dusk196/github-repo-stats?style=for-the-badge&color=3ddc97
```
