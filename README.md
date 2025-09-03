# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### NAME: HEMAMALINI S                                                                          
### REGISTER NUMBER : 212222210006
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm: 


---

# 🍴 Food Menu Nutritional Chart

**Dish name, ingredients, calories, protein, fat, and allergen info structured for easy reading.**

---

## ⚙️ Algorithm Application

### 1. **Direct Instruction Prompting**

**Objective:** Guide the chatbot to respond concisely to customer inquiries.
**Prompt Pattern:**
Prompt: *"Generate a Food Menu Nutritional Chart showing dish name, ingredients, calories, protein, fat, and allergen info. Present the data clearly in a tabular column for easy comparison, and attach related food pictures for each dish."*

---

### 2. **Contextual Prompting**

**Objective:** Incorporate specific context to provide detailed answers based on the user’s previous interaction.
**Prompt Pattern:**
Prompt: *"If the user asks for details of specific dishes, present their ingredients, nutritional values, and allergens in a structured table, while also showing images of the dishes for better understanding."*

---

### 3. **Persona-Based Prompting**

**Objective:** Design the chatbot to adopt a specific persona, making the interaction more engaging.
**Prompt Pattern:**
Prompt: *"Act like a nutritionist and friendly restaurant assistant. Explain each dish in a helpful, conversational tone. Example: 'Here’s a breakdown of the dish so you can easily compare calories, protein, and allergens!'"*

---

### 4. **Few-Shot Prompting**

**Objective:** Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.
**Prompt Pattern:**
Prompt:
*"Here are examples:*

* Dish: *Grilled Chicken Salad* → Ingredients: Chicken, lettuce, tomatoes, olive oil → Calories: 350 → Protein: 30g → Fat: 15g → Allergen: None → Image: Salad picture.
* Dish: *Cheese Pizza* → Ingredients: Wheat flour, cheese, tomato sauce → Calories: 600 → Protein: 20g → Fat: 22g → Allergen: Gluten, Dairy → Image: Pizza picture.

*Now, generate a table for multiple dishes with the same format."*

---

### 5. **Chain of Thought Prompting**

**Objective:** Use a step-by-step reasoning approach for resolving more complex or technical issues.
**Prompt Pattern:**
Prompt: \*"To prepare the Food Chart, follow these steps:

1. List dish names.
2. Break down main ingredients.
3. Add calories, protein, and fat per serving.
4. Highlight possible allergens (gluten, nuts, dairy, etc.).
5. Create a comparison table.
6. Insert relevant food pictures.
   Now, apply this to build the chart."\*

---

### 6. **Instruction with Constraints**

**Objective:** Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).
**Prompt Pattern:**
Prompt: *"Keep the table clean and readable with no more than 8 columns. Use short descriptions for ingredients. Provide 1 clear picture per dish. Keep text concise but informative."*

---

### 7. **Reflective Prompting**

**Objective:** Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.
**Prompt Pattern:**
Prompt: *"When a user asks 'What’s the nutritional value of this dish?', first reflect it: 'You’d like to know the nutritional breakdown for this dish, correct?' Then, show them the table row for that dish with an image."*

**Table**


| Dish Name             | Ingredients (short)                         | Calories (per serving) | Protein (g) | Fat (g) | Allergen Info      | Image 📸           |
| --------------------- | ------------------------------------------- | ---------------------- | ----------- | ------- | ------------------ | ------------------ |
| Grilled Chicken Salad | Chicken, lettuce, tomatoes, olive oil       | 350                    | 30          | 15      | None               | 🥗 Salad picture   |
| Cheese Pizza          | Wheat flour, cheese, tomato sauce           | 600                    | 20          | 22      | Gluten, Dairy      | 🍕 Pizza picture   |
| Veggie Burger         | Bun, veggie patty, lettuce, tomato, mayo    | 450                    | 18          | 20      | Gluten, Soy        | 🍔 Burger picture  |
| Spaghetti Bolognese   | Pasta, minced beef, tomato sauce, olive oil | 550                    | 25          | 19      | Gluten             | 🍝 Pasta picture   |
| Chocolate Brownie     | Cocoa, flour, sugar, butter, eggs           | 420                    | 6           | 22      | Gluten, Dairy, Egg | 🍫 Brownie picture |





# Result: Thus the Prompts were exected succcessfully .

