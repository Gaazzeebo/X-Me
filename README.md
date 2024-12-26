# README

**Author:** **Jack Liselli, Founder & CEO**

## Overview
This repository contains **25 standalone web pages**, each featuring a **unique Bible verse**. The end goal is to host each page separately so that each verse has its own direct link, which can then be converted into a QR code.  

Below, you will find the **complete list** of Bible verses, detailed **instructions**, and **example code snippets** to guide you through the development process.

---

## Instructions

1. **Create 25 Individual Pages**  
   - Each page corresponds to **one** Bible verse.  
   - Name the HTML files as `page1.html`, `page2.html`, etc.  
   - **No linking** to an index or other scripture pages; **each** stands alone.

2. **Attach Unique CSS to Each Page**  
   - For each HTML file (e.g., `page1.html`), create a dedicated CSS file (e.g., `style1.css`).  
   - Each page should have a **distinct** design while maintaining a cohesive theme (uplifting, positive, and professional).

3. **Footer Requirements**  
   - At the bottom of **each** page, insert the text:
     ```
     Powered by Gaazzeebo
     ```
     in **glowing electric orange**.  
   - Include a clickable link to [Gaazzeebo.net](http://gaazzeebo.net) adjacent to or below that text.

4. **Hosting & QR Codes**  
   - Push all files to the existing GitHub repository.  
   - Each page will have a **unique hosted URL**—these URLs will be used to generate QR codes.  
   - Ensure there are **no** links back to a central `index.html`.

5. **Design & Testing**  
   - **Responsive Layout**: Make sure each page is readable on desktop and mobile devices.  
   - **Check Verses**: Verify each verse is accurately included.  
   - **Footer Check**: Confirm the glow effect for "Powered by Gaazzeebo" and that the link to Gaazzeebo.net is functional.

6. **Deliverables**  
   - A **list of 25 direct URLs** for each of the scripture pages, once pushed to the GitHub repository.  
   - This will allow straightforward QR code generation.

---

## Bible Verses

Include **one** of these verses on **each** corresponding page (i.e., `page1.html` for #1, `page2.html` for #2, etc.):

1. **Jeremiah 29:11**  
   “For I know the plans I have for you,” declares the Lord, “plans to prosper you and not to harm you, plans to give you hope and a future.”

2. **Philippians 4:13**  
   “I can do all things through Christ who strengthens me.”

3. **Proverbs 3:5-6**  
   “Trust in the Lord with all your heart and lean not on your own understanding; in all your ways submit to Him, and He will make your paths straight.”

4. **Isaiah 40:31**  
   “But those who hope in the Lord will renew their strength. They will soar on wings like eagles; they will run and not grow weary, they will walk and not be faint.”

5. **Romans 8:28**  
   “And we know that in all things God works for the good of those who love Him, who have been called according to His purpose.”

6. **Matthew 19:26**  
   “With man this is impossible, but with God all things are possible.”

7. **Psalm 23:1-3**  
   “The Lord is my shepherd; I shall not want. He makes me lie down in green pastures. He leads me beside still waters. He restores my soul.”

8. **2 Timothy 1:7**  
   “For the Spirit God gave us does not make us timid, but gives us power, love, and self-discipline.”

9. **Joshua 1:9**  
   “Have I not commanded you? Be strong and courageous. Do not be afraid; do not be discouraged, for the Lord your God will be with you wherever you go.”

10. **Psalm 46:1-2**  
    “God is our refuge and strength, an ever-present help in trouble. Therefore we will not fear, though the earth give way and the mountains fall into the heart of the sea.”

11. **Ephesians 3:20**  
    “Now to Him who is able to do immeasurably more than all we ask or imagine, according to His power that is at work within us.”

12. **Deuteronomy 31:6**  
    “Be strong and courageous. Do not be afraid or terrified because of them, for the Lord your God goes with you; He will never leave you nor forsake you.”

13. **Psalm 37:4**  
    “Take delight in the Lord, and He will give you the desires of your heart.”

14. **Matthew 6:33**  
    “But seek first His kingdom and His righteousness, and all these things will be given to you as well.”

15. **John 16:33**  
    “I have told you these things, so that in Me you may have peace. In this world you will have trouble. But take heart! I have overcome the world.”

16. **Psalm 121:1-2**  
    “I lift up my eyes to the mountains—where does my help come from? My help comes from the Lord, the Maker of heaven and earth.”

17. **Proverbs 18:10**  
    “The name of the Lord is a fortified tower; the righteous run to it and are safe.”

18. **Isaiah 41:10**  
    “So do not fear, for I am with you; do not be dismayed, for I am your God. I will strengthen you and help you; I will uphold you with my righteous right hand.”

19. **Psalm 27:1**  
    “The Lord is my light and my salvation—whom shall I fear? The Lord is the stronghold of my life—of whom shall I be afraid?”

20. **Romans 12:2**  
    “Do not conform to the pattern of this world, but be transformed by the renewing of your mind. Then you will be able to test and approve what God’s will is—His good, pleasing and perfect will.”

21. **James 1:2-3**  
    “Consider it pure joy, my brothers and sisters, whenever you face trials of many kinds, because you know that the testing of your faith produces perseverance.”

22. **Matthew 5:16**  
    “In the same way, let your light shine before others, that they may see your good deeds and glorify your Father in heaven.”

23. **1 Corinthians 16:13**  
    “Be on your guard; stand firm in the faith; be courageous; be strong.”

24. **Hebrews 11:1**  
    “Now faith is confidence in what we hope for and assurance about what we do not see.”

25. **Colossians 3:23**  
    “Whatever you do, work at it with all your heart, as working for the Lord, not for human masters.”

---

## Example HTML Structure

Below is an **example** for `page1.html`. Adapt this structure for all 25 pages:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Page 1 - Jeremiah 29:11</title>
  <!-- Link to the unique CSS file for this page -->
  <link rel="stylesheet" href="style1.css" />
</head>
<body>
  <div class="container">
    <h1>Jeremiah 29:11</h1>
    <p>
      "For I know the plans I have for you," declares the Lord, 
      "plans to prosper you and not to harm you, plans to give you hope 
      and a future."
    </p>
  </div>

  <footer>
    <p>
      <span class="powered-by">Powered by Gaazzeebo</span>
      |
      <a href="http://gaazzeebo.net" target="_blank">Gaazzeebo.net</a>
    </p>
  </footer>
</body>
</html>


/* style1.css for page1.html */

body {
  margin: 0;
  padding: 0;
  font-family: "Arial", sans-serif;
  background: #f0f8ff;
}

.container {
  max-width: 600px;
  margin: 5% auto;
  padding: 0 1rem;
  text-align: center;
}

h1 {
  color: #333;
  margin-bottom: 1rem;
}

p {
  font-size: 1.2rem;
  line-height: 1.4;
  color: #555;
}

footer {
  position: fixed;
  bottom: 0;
  width: 100%;
  text-align: center;
  background: #ffffffcc;
  padding: 0.5rem;
}

.powered-by {
  color: #ff6600; /* Glowing electric orange */
  font-weight: bold;
  text-shadow: 0 0 4px rgba(255, 102, 0, 0.7),
               0 0 8px rgba(255, 102, 0, 0.5);
}
