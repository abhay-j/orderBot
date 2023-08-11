
# Haandi Fine Indian Cuisine Orderbot

This program simulates an automated service, Orderbot, for taking "pick-up" orders from customers at the restaurant "Haandi Fine Indian Cuisine." Orderbot interacts with customers, takes their orders, provides order summaries, estimates pickup times, and collects payment information.

## Features

- Greets customers and takes their orders.
- Summarizes orders and provides estimated pickup times.
- Collects credit card details from customers.
- Responds in a short, conversation-friendly style.
- Provides menu options for various cuisines.
- Operates from 11 AM to 2 PM and 5 PM to 8:30 PM EST.

## How to Run

1. Make sure you have Python installed on your machine.
2. Install the required dependencies using the following command:

   ```bash
   pip install openai

3. Replace os.environ.get("API_KEY") with your OpenAI API key.
4. Run the program by executing the Python script:
  
 
   ```bash
   python orderbot.py

## Example Interaction

- Customer: Can I place an order?
- Orderbot: Hello! Welcome to Haandi Fine Indian Cuisine. Of course, you can place an order. What would you like to order?
- Customer: I'll have the Chicken Tikka Masala.
- Orderbot: Great choice! Anything else you'd like to add to your order?
- Customer: Yes, please add a Garlic Naan as well.
- Orderbot: Noted. Is there anything else you'd like to order?
- Customer: No, that's it. How long will it take to prepare?
- Orderbot: Your order will be ready for pickup in approximately 20 minutes. Please provide your credit card details to confirm the order.
- Customer: Sure, here's my credit card information.
- Orderbot: Thank you for providing your credit card details. Your order has been confirmed. You can pick it up in about 20 minutes. Enjoy your meal!
- Customer: Thank you!
- Orderbot: You're welcome! If you need any further assistance, feel free to ask.
- Customer: Goodbye.
- Orderbot: Goodbye, and have a wonderful day!
Conversation Ended

## Notes

- This program uses OpenAI's GPT-3.5 Turbo model for natural language processing.
- The current time is displayed in conversation for reference.
- Ensure you adhere to OpenAI's usage policies and guidelines while using this program.
- For any issues or feedback, please contact the developer at jabhay2012@gmail.com.







