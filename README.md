# 📒 Bomion - Web App like Notion
<img width="1582" alt="bomion" src="https://github.com/bibidibovidiboo/bomion-like-notion/assets/66943451/91b1ec8f-2bcb-4f08-a42c-ec61d552d9a9">

**Bomion like in Notion. Full-stack Wep App using Next.js**

- Next.js, React, Convex, TailwindCSS 등을 활용하여 개발된 노션과 유사한 웹 애플리케이션입니다. <br />
- [해당 튜토리얼](https://www.youtube.com/watch?v=0OaDyjB9Ib8)을 참고하여 Next.js 13을 기반으로한 서비스를 풀스택으로 만들어보고자 개발되었습니다.

<br />

## Tech Stack
`Next.js` `React.js` `TypeScript` `Convex` `Clerk` `TailwindCSS` 

<br />

## Key Features

- Real-time database  🔗 
- Notion-style editor 📝 
- Light and Dark mode 🌓
- Infinite children documents 🌲
- Trash can & soft delete 🗑️
- Authentication 🔐 
- File upload
- File deletion
- File replacement
- Icons for each document (changes in real-time) 🌠
- Expandable sidebar ➡️🔀⬅️
- Full mobile responsiveness 📱
- Publish your note to the web 🌐
- Fully collapsable sidebar ↕️
- Landing page 🛬
- Cover image of each document 🖼️
- Recover deleted files 🔄📄

<br />

## Installation

**1. Clone the project**

```
git clone https://github.com/bibidibovidiboo/fullstack-notion-clone.git
```

**2. Install packages**

```
npm i
```
**3. Add environment variables**

Create `.env` and `auth.config.js` files

```js
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Edge Store environment variables
EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

```js
export default {
  providers: [
    {
      domain: "https://your-issuer-url.clerk.accounts.dev",
      applicationID: "convex",
    },
  ]
};
```

**4. Setup Convex**

```
npx convex dev
```

**5. Start the app**

```
npm run dev
```

<br />

## Reference
- [Setup Convex](https://docs.convex.dev/quickstart/nextjs)
- [Convex Clerk](https://docs.convex.dev/auth/clerk)
- [Edge Store](https://edgestore.dev/docs/quick-start)
