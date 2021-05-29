# extract_Name_from_email
"""This program is used to extract name from given email address. It uses list slicing technique."""
def username(email_id):
    return email_id[:email_id.index("@")]
u1 = username("john@xmail.com")
u2 = username("jack@zmail.com")
print(u1, u2)
