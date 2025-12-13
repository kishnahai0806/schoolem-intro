# SchoolEm – Production Frontend

This repository is the **production frontend** for **SchoolEm**, a social platform built for college students to connect, collaborate, and discover what’s happening on their campus.

**Note:** This repo is a fork of `Wuizlz/schoolem-intro` and is used as the deployment source for the live site.

## 🌐 Live Application
**Production:** https://officialschoolem.org  
Deployed via **Vercel**, connected to this repository’s **`main`** branch (every push to `main` triggers a production deploy).

## 🚀 What is SchoolEm?
SchoolEm is a campus-focused social media platform inspired by apps like Instagram and YikYak. It gives students a dedicated space to:
- Post and share updates with their university community  
- Discover and promote clubs, events, and student projects  
- Find study groups and like-minded people  
- Speak more freely than on traditional school-run apps  

## 🧰 Tech Stack
- **Frontend:** React (SPA)
- **Routing:** React Router
- **Styling:** Tailwind CSS + styled-components (hybrid)
- **State/Data:** React Query + custom hooks
- **Backend-as-a-Service:** Supabase (Postgres, Auth, RLS)
- **Deployment:** Vercel
- **Auth:** Supabase email-based auth (university email domain restricted)

## 🧾 Repo Relationship
- **Upstream (original dev repo):** `Wuizlz/schoolem-intro`
- **This fork (production):** `kishnahai0806/schoolem-intro`
- **Production branch:** `main` (connected to Vercel)
