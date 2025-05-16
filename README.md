# Python-projects 
# Email Slicer project
email = input("Please enter Your Email: ").strip()

username = email[:email.index('@')]
domain_name = email[email.index('@') + 1:]

print(f"Your username is {username} & domain is {domain}")
