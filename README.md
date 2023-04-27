<div align="center">
<a href="https://moopa.live">
  <img src="https://user-images.githubusercontent.com/97084324/234460363-216b29d3-acba-4c29-a321-780de84c9ab0.png" alt="logo" width="180"/>
</a>
</div>

<h1 align="center">
  <a href="https://moopa.live">Moopa Anime Streaming Website</a>
</h1>

<p align="center">

 <a href="https://github.com/DevanAbinaya/Ani-Moopa/blob/main/LICENSE.md">
    <img src="https://img.shields.io/github/license/DevanAbinaya/Ani-Moopa" alt="license"/>
  </a>
  <a href="https://github.com/DevanAbinaya/Ani-Moopa/fork">
    <img src="https://img.shields.io/github/forks/DevanAbinaya/Ani-Moopa?style=social" alt="fork"/>
  </a>
  <a href="https://github.com/DevanAbinaya/Ani-Moopa">
    <img src="https://img.shields.io/github/stars/DevanAbinaya/Ani-Moopa?style=social" alt="stars"/>
  </a>
  
</p>

<p align="center"><a href="https://moopa.live">Moopa</a> is an anime streaming website build with nextjs and tailwindcss with a sleek and modern design that offers Anilist integration to help you keep track of your favorite anime series. Moopa is entirely free and does not feature any ads, making it a great option for you who want an uninterrupted viewing experience.</p>

![image](https://user-images.githubusercontent.com/97084324/234473045-8c648633-1f85-4815-b784-75d32bbdc2a7.png)


<details>
<summary>More Screenshots</summary>

<h5 align="center">Home page after you login</h5>
<img src="https://user-images.githubusercontent.com/97084324/234463979-4b4fa1ba-34cb-4ae4-b4e1-59500b24ac6f.png"/>

<h5 align="center">Profile Page</h5>
<img src="https://user-images.githubusercontent.com/97084324/234556937-76ec236c-a077-4af5-a910-0cb85e900e38.gif"/>

<h5 align="center">Info page for PC/Mobile</h5>
<p align="center">
<img src="https://user-images.githubusercontent.com/97084324/234508708-082b8d64-1dea-4525-98a5-51a5a95e8db3.png"/>
</p>

<h5 align="center">Watch Page</h5>
<img src="https://user-images.githubusercontent.com/97084324/234466915-c2107ee5-5cfe-4cf5-9da4-9ad02aaf066a.png"/>
 
</details>

## Features

- Free ad-supported streaming service
- Anime tracking through Anilist API
- User-friendly interface
- Mobile-responsive design
- PWA supported

## To Do List

- [x] Add PWA support
- [x] Connect to consumet API to fetch episodes data
- [x] Implement skip op/ed button on supported anime
- [x] Create README file
- [ ] Integrate Anilist API for anime tracking
  - [x] Ability to auto track anime after watching >= 90% through the video
  - [x] Create a user profile page to see lists of anime watched
  - [ ] Ability to edit list inside detail page
- [ ] Working on Manga pages

## For Local Development

1. Clone this repository using :
```bash
git clone https://github.com/DevanAbinaya/Ani-Moopa.git
```
2. Install package using npm :
```bash
npm install
```
3. Create ```.env``` file in the root folder and put this inside the file :
```bash
CLIENT_ID="get the id from here https://anilist.co/settings/developer"
CLIENT_SECRET="get the secret from here https://anilist.co/settings/developer"
GRAPHQL_ENDPOINT=https://graphql.anilist.co
NEXTAUTH_SECRET='type this in your bash terminal (openssl rand -base64 32) with no bracket and paste it here'
NEXTAUTH_URL="for development use http://localhost:3000/ and for production use your domain url"
```
4. Start local server :
```bash
npm run dev
```

## Credits

- [Consumet API](https://github.com/consumet/api.consumet.org)
- [AniList API](https://github.com/AniList/ApiV2-GraphQL-Docs)
- [miru](https://github.com/ThaUnknown/miru/blob/master/README.md?plain=1) for inspiring me making this site

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

Thank You for passing by!! If you have any questions or feedback, please reach out to us at [factiven.org@gmail.com](mailto:factiven.org@gmail.com), or you can join our [discord sever](https://discord.gg/4xTGhr85BG).

## Support This Project
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/E1E6F9XZ3)
