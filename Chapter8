
def inventory_quiz():
    questions = [
    {
        "question": "What best defines inventory?",
        "options": {
            "a": "Goods ready for immediate resale to customers",
            "b": "A stock over which value is constantly added",
            "c": "Stock owned by a company, but no value is added yet",
            "d": "Items held by suppliers on behalf of a firm"
        },
        "answer": "c"
    },
    {
        "question": "Why is minimizing inventory important for firms?",
        "options": {
            "a": "Inventory boosts short-term profits",
            "b": "It ensures higher turnover of fixed assets",
            "c": "Inventory is expensive and difficult to convert into cash",
            "d": "It reduces the need for production planning"
        },
        "answer": "c"
    },
    {
        "question": "What are the three main types of inventory?",
        "options": {
            "a": "Materials, shipments, and backups",
            "b": "Raw materials, WIP, and finished goods",
            "c": "Work orders, shipments, and returns",
            "d": "Pre-sales, post-sales, and packaging"
        },
        "answer": "b"
    },
    {
        "question": "What type of inventory includes components being assembled?",
        "options": {
            "a": "Finished goods",
            "b": "Rework inventory",
            "c": "Work-in-process",
            "d": "Raw materials"
        },
        "answer": "c"
    },
    {
        "question": "What is a key function of an inventory system?",
        "options": {
            "a": "Forecasting labor cost",
            "b": "Managing facility layout",
            "c": "Monitoring levels and determining reorder timing",
            "d": "Determining capital structure"
        },
        "answer": "c"
    }
]
    
    for idx, q in enumerate(questions, 1):
        while True:
            print(f"\nQuestion {idx}: {q['question']}")
            for opt, text in q['options'].items():
                print(f"  {opt}) {text}")
            answer = input("Your answer (a, b, c, or d): ").lower().strip()
            if answer == q['answer']:
                print("Correct!")
                break
            else:
                print("Incorrect. Please try again.")

inventory_quiz()
