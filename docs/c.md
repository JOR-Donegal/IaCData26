# YAML

_YAML_ (YAML Ain't Markup Language) is minimalist compared to XML or JSON and is used by some automation tools, notably Ansible. It has also become the file format of choice in Ubuntu and some web configuration tools.

Data is represented as _key-value pairs_, _lists_ and _nested objects_.

Structure is created using _indentation_.

```yaml
# Key value pairs 
first_name:"John",
surname : "ORaw",
````

```yaml
# Lists
Modules:
  - IaC
  - Networking
  - Hybrid
  - Storage
````

```yaml
# Nested Objects
person: 
  first_name:"John",
  surname : "ORaw",
  address:
    house: The Aras
    street: phoenix park
    city: dublin  
```

```yaml
# Lists of objects
Modules:
 - name: IaC
   description: Infrastructure as Code 
 - name: Networking
   description: Introduction to Networking 
    
```

YAML is very easy for humans to read and is by far the most economical and efficient of the data formats discussed. However it requires consistent indentation, normally two spaces. I am sometime lazy and without thinking, I use a tab. This will work on some systems and then fail miserably when I do not expect it to!

Some users criticize it 

__Use two spaces for indentation__.