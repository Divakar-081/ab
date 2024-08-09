tasks=[]
def displaytask():
    print("here are the tasks")
    print(task)
def addtask():
    task=input("Enter a task to be added")
    task.append(tasks)
    print(f"TAsk {task} added to the list")
def removetask():
    task=input("Enter task to remove")
    if task in tasks:
        task.remove(tasks)
        print(f"Task {task} is removed")
    else:
        print(f"Task {task} is not found")

while True:
    print("Please select your task")
    print("1. Display the task")
    print("2. Add the task")

    print("4. Remove the task ")
    print("5. Quit")
    choice=input("enter your choice")
    if choice=="1":
        displaytask()

    elif choice=="2":
        addtask()



    elif choice=="4":
        removetask()

    elif choice=="5":
        break

    else:
        print("invalid input. Try again")

