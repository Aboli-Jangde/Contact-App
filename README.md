# Contact-App

from IPython.display import clear_output

while True:
    
  def show_contacts(contacts):
    return contacts
  # contacts
  show_contacts(contacts)

  action = input("Press 'a' - add contact, 'o' - open contact, 's' - search contact, 'q' - quit")
  if action == 'a':
          def add_contact(contacts):
            add = {}
            add['name']=input()
            add['number']=input()
            add['email']=input()
            contacts.append(add)
            return contacts
            contacts
          add_contact(contacts)

  elif action == 'o':
          name = input("Enter name of the contact you want to open. ")        
          def open_contact(contacts, name):
            for i in contacts:
              if i['name']==name:
                return i
            else:
              print("No match Found")
          open_contact(contacts,'aaa')

  elif action == 'q':
    break
      
  else:
    print("Incorrect option")
    
    fw = open('/content/contacts.txt', 'a') # write mode
fw.write('This is written by python.')
fw.close()
