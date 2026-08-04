# Simple To-Do List

tasks = []

while True:
    print("\n1. Add Task")
    print("2. View Tasks")
    print("3. Exit")

    choice = input("Enter your choice: ")

    if choice == "1":
        task = input("Enter the task: ")
        tasks.append(task)
        print("Task added.")

    elif choice == "2":
        if len(tasks) == 0:
            print("No tasks available.")
        else:
            print("Your Tasks:")
            for task in tasks:
                print("-", task)

    elif choice == "3":
        print("Program closed.")
        break

    else:
        print("Invalid choice.")
