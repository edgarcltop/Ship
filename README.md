# Ship - A batteries included Svelte 5 SaaS Boilerplate

### Comes With

- 💻 **Svelte 5 and SvelteKit 2**
- 🚪 **Auth** (both social and magic link, using Lucia)
- 📧 **Sending Emails** (using Postmark)
- 🎨 **Styling** (using tailwindcss and shadcn)
- 📦 **Database** (using turso and drizzle as ORM)
- ☁️ **Serverless hosting** using vercel

### Getting Started 🚀

#### Local Development

- Run `pnpm install`
- Rename the `.env.example` file to `.env` and **populate it with your own values**
- Run `npm run generate && npm run migrate` to create a local database
- Install mailpit to receive emails locally https://mailpit.axllent.org/docs/install/
- run `npm run dev`

#### Production 🌐

- 🌍 Get a domain name
- 📬 Create a **postmark** account and get the server api key
- 💾 Set up a database with **Turso**: [Turso Setup](https://turso.tech/)
- 🔑 Create an OAuth credential in **Google Cloud**
- 🎯 Point your main domain name to your project on Vercel
- 🔐 fill out the environment variables in `.env`
- ⚙️ Add those environment variables to your project in Vercel

Feel free to contribute or suggest improvements! 🤝

### How to setup Just Ship the youtube tutorial
(note this tutorial is slightly outdated) You don't need mailpit neccesarily I log the email login link in the console. 
I also use shadcn now instead of daisyUI
