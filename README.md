# LinkedIn Post Generator (n8n Automation)

## 📌 Overview
This automation helps generate **engaging LinkedIn posts** complete with:
- AI-generated content tailored to a chosen topic and target audience.  
- AI-generated graphics to visually support the post.  
- Automatic LinkedIn publishing (optional).  
- Email confirmation when the post is ready.  

It streamlines content creation for professionals, marketers, and businesses who want to stay consistent on LinkedIn without spending hours drafting and designing posts.

---

## ⚙️ How It Works
1. **Trigger (Form Submission)**  
   - User fills out a form with their **email**, **post topic**, and **target audience**.

2. **Generate Post Content**  
   - Uses **OpenAI GPT-4o** to research and craft a professional LinkedIn post.  
   - Ensures a clear, engaging structure with actionable insights.  

3. **Create Title**  
   - AI generates a concise, attention-grabbing title for the LinkedIn post.

4. **Generate Image Prompt & Design**  
   - AI converts the post into a **visual prompt**.  
   - The system calls **OpenAI image generation API** to create a 1024×1024 marketing-style graphic.  

5. **Convert & Publish**  
   - Image is converted to a file format.  
   - Post (with title, description, and image) can be published directly to **LinkedIn** (disabled by default).  

6. **Send Confirmation Email**  
   - User receives an email containing the generated post details.

---

## 📂 Files
- `Linkdein_Post_Generator.json` → Exported n8n workflow.  
- `README.md` → Documentation (this file).  

---

## 🚀 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/linkedin-post-generator.git
   cd linkedin-post-generator
