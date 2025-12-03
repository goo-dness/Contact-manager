#Contact Manager
contacts = {} # an empty dictionary to store contacts 
print("=" * 40)
print("CONTACTS MANAGER")
print("=" * 40)

while True:
    print("Menu:")
    print("1. Add contact")
    print("2. View contacts")
    print("3. Search contact")
    print("4. Delete contact ")
    print("5. Quit ")
    choice = input("Choose option (1-5): ")
    if choice == "1":
       #Add contacts 
       name = input("Enter name: ").title()
       phone = input("Enter phone number: ")
       contacts[name] = phone
       print(f"{name} added successfully")
    elif choice == "2":
      #View contacts 
      if len(contacts) == 0:
          print("No contacts yet.")
      else:
          print("Your contacts.")
      for name, phone in contacts.items ():
            print(f"{name}: {phone}")
    elif choice =="3":
         #search contacts
         search_name = input("Enter a name to search contacts: ")
         if search_name in contacts:
           print(f"{search_name}:  {contacts [search_name]}")
         else :
           print(f"{search_name}, not found!")
        
        #Delete contacts 
    elif choice == "4":
         delete_name = input("Enter a name to delete: ")
         if delete_name in contacts:
            print(f"Delete {delete_name}")
         else:
             print(f"{delete_name} not found!")
             
    elif choice == "5":
              #quit
            print("Goodbye")
            break
    
    else:
            print("Invalid choice, please choose (1-5).")
     
     
            print("Final contacts lists")
            for name, phone in contacts.items():
                print(f"{name}: {phone}")
