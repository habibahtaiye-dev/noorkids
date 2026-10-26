# NoorKids — Islamic Learning for Children

Responsive, independently built Islamic learning web app starter. It does not include Fullk's private source code or proprietary assets.

## Included
- Responsive dashboard, lessons, quiz and parent area
- English, Hausa and Yoruba interface switching
- Sample Arabic letters lesson
- Search and category filters
- Browser-local lesson completion tracking
- Demo parent gate

## Run locally
Requires Node.js 20+.
```bash
npm install
npm run dev
```
Open the URL shown in the terminal.

## Deploy on Vercel
1. Upload this project to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Set build command `npm run build` and output directory `dist`.
4. Click **Deploy**. `vercel.json` is included for client-side routes.

## Deploy on Netlify
Import the GitHub repo. Set build command `npm run build` and publish directory `dist`.

## Before public launch
This is a frontend demo only: no backend, secure accounts, cloud sync, real audio library or CMS. The parent gate is not security. Review Islamic content and translations with qualified educators/native speakers. Add privacy policy, parental consent, and child-safety review before collecting child data.
