# AI-Task-Classifier

A lightweight, interactive web app that uses a HuggingFace transformer model to classify tasks into categories like Work, Personal, or Study — complete with confidence scores, color tags, sound alerts, and editable category options.

---

🔍 Features

- Add multiple tasks with date & time.
- Classify tasks using the BART-Large-MNLI model from Hugging Face.
- Automatically suggests a category based on task description.
- Assigns a unique color per category.
- Provides confidence score for each classification.
- Includes a sound notification on completion.
- Editable task rows and easy row removal.
- 🔧 **Add your own custom categories via UI.**  
  (No more editing code or localStorage manually!)

---

🚀 Demo  
_(Coming soon: hosted demo link or GIF preview)_

---

🧰 Tech Stack

- HTML, CSS, JavaScript
- Hugging Face Inference API
- Model: `facebook/bart-large-mnli`

---

📦 Use Cases

🗂️ Productivity apps: Automatically tag tasks by intent  
👩‍🎓 Student dashboards: Auto-sort study vs personal vs work tasks  
🧪 AI Inference Demos: Show quick NLP classification in action  
🧑‍💼 Personal planners: Categorize without manual tagging

---

🧠 How It Works

1. Type a task (e.g., “Submit final project report”).
2. Click "🤖 Classify with AI".
3. The app sends your task to the Hugging Face API.
4. It returns the most likely category and confidence score.
5. A unique color is generated and applied for clarity.
6. You can also manually select or **create new categories**.

---

🛠️ Local Setup

```
git clone https://github.com/yourusername/ai-task-classifier.git
cd ai-task-classifier
open index.html
```

🔐 Notes

  Requires a Hugging Face API token — get yours at https://huggingface.co/.

  Default categories include Work, Personal, Study, etc.

  Categories are now fully editable and expandable via the UI.

  All task data and categories are saved using localStorage.

📌 Todo / Enhancements

  ✅ Add color assignment per category
  ✅ Play sound on classification completion
  ✅ Allow dynamic category creation (via input field + button)
  ✅ Add persistent local storage for tasks
  ⬜ Option to export/import task list
  ⬜ Mobile responsive version
  ⬜ Dark mode support

Screenshots
<img width="1391" alt="Screenshot 2025-05-29 at 7 31 12 PM" src="https://github.com/user-attachments/assets/565db2fc-c208-49dc-9911-5eb0cbfcb73b" /><img width="1382" alt="Screenshot 2025-05-29 at 7 29 49 PM" src="https://github.com/user-attachments/assets/abf36b6f-e32a-439f-adaa-c7206b838dbf" /><img width="921" alt="Screenshot 2025-05-29 at 7 07 22 PM" src="https://github.com/user-attachments/assets/254fec63-c6da-4009-9318-043895295337" />
[![Made with ❤️ by Yalamarthi Nagadivya]
[![Hugging Face Model]
[![Built with JavaScript]
