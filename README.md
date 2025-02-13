# Study MBBS Abroad - University Insights

## 📌 Project Overview
This is a **responsive landing page** for **Study MBBS Abroad**, designed to provide information about studying MBBS in different countries. It includes country listings, program details, and a lead generation form.

## 🎯 Features
- **Responsive Design** using **Tailwind CSS**
- **SEO-Optimized Content** for better search visibility
- **Lead Generation Form** with validation
- **Google Analytics & Facebook Pixel** for tracking
- **Fast Loading & Mobile Friendly**
- **Deployed on Vercel** for easy access

## 🛠️ Technologies Used
- **HTML, CSS (TailwindCSS), JavaScript**
- **PHP (Optional for backend validation)**
- **Google Analytics & Facebook Pixel** for tracking
- **Vercel** for deployment

## 🚀 Setup Instructions
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/YOUR-USERNAME/study-mbbs-abroad.git
cd study-mbbs-abroad
```

### **2️⃣ Open in VS Code**
```sh
code .
```

### **3️⃣ Run Locally**
Since it's a static site, open `index.html` in a browser or use Live Server:
```sh
npx live-server
```
_(Make sure you have Node.js installed to use `npx`)_

### **4️⃣ Deploy on Vercel**
1. **Sign up/log in** to [Vercel](https://vercel.com/)
2. **Import your GitHub repo**
3. **Deploy & Get Live URL**

## 🔍 Tracking Setup
### **Google Analytics**
- Add your **GA4 Tracking ID** inside `index.html`:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

### **Facebook Pixel**
- Replace `YOUR_PIXEL_ID` inside `index.html`:
```html
<script>
  fbq('init', 'YOUR_PIXEL_ID');
  fbq('track', 'PageView');
</script>
```

## 💡 Contribution
Feel free to fork, modify, and submit pull requests!

## 📜 License
This project is **open-source** under the **MIT License**.

