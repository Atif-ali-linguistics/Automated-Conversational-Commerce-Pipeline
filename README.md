# Automated-Conversational-Commerce-Pipeline
1. Project Overview
Developed a zero-dependency, dynamic Single Page Application (SPA) to digitize restaurant order processing and streamline customer-to-business communication.
2. Methodology (Prompt Architecture)
Engineered structured LLM prompts imposing strict technical constraints to generate modular vanilla JavaScript, CSS Grid/Flexbox layouts, and dynamic DOM manipulation without relying on external libraries.  
​3. State Management & Data Parsing
Implemented client-side state management using a dynamic JavaScript object (let cart = {}) to track user selections, calculate billing totals, and update the UI asynchronously.  
​4. The WhatsApp Automation Pipeline
Developed a custom confirmOrder() function that extracts user inputs (Name, Phone, Address) alongside cart data, formats it into a readable invoice string, applies URI encoding (encodeURIComponent), and dynamically routes the payload to the WhatsApp API for instant order transmission. 
