# tf-bootcamp
# Writing good documentation

## Step 1 - Using codeblocks. 

Codeblocks in markdown make it **very easy** for *tech* people to copy, paste, share code. 
A good cloud engineer uses codeblocks whenever possible. 

Because it allows others to copy and paste their codes to replicate or research issues. 

- In order to create codeblocks in markdown, you need to use three backticks (`). 
- Not to be mistaken with single quotations or apostrophes.

```
class Person
  attr_accessor :name, :age

  def initialize(name, age)
    @name = name
    @age = age
  end

  def introduce
    puts "Hi, I'm #{@name} and I'm #{@age} years old."
  end
end

# Create an instance of the Person class
person1 = Person.new("John Doe", 30)

# Access and modify instance variables
person1.name = "Jane Smith"
person1.age = 35

# Call a method on the instance
person1.introduce

```

- When you can, you should attempt to apply syntax highlighting to your codeblocks.


```ruby
class Person
  attr_accessor :name, :age

  def initialize(name, age)
    @name = name
    @age = age
  end

  def introduce
    puts "Hi, I'm #{@name} and I'm #{@age} years old."
  end
end

# Create an instance of the Person class
person1 = Person.new("John Doe", 30)

# Access and modify instance variables
person1.name = "Jane Smith"
person1.age = 35

# Call a method on the instance
person1.introduce

```

`` ![image](https://github.com/Tobydiah/tf-bootcamp/assets/28768860/f262ab6c-d390-4107-a9bb-b1cdbd3e93e9) ``

<img src="https://github.com/Tobydiah/tf-bootcamp/assets/28768860/f262ab6c-d390-4107-a9bb-b1cdbd3e93e9" alt="Alt text" width="200"/>



Good cloud engineers use codeblocks for both code and errors that appear in the console. 

```bash
def perform_calculation
  result = 10 / 0  # This will raise a ZeroDivisionError
  puts "Result of the calculation: #{result}"
end

def main
  puts "Starting calculation..."
  perform_calculation
  puts "Calculation complete."
end

main
```
> Here is an example of using a codeblock for an error that appears in bash.

This is an example of a checklist: 👍

- [x] Eat
- [x] Sleep
- [ ] Study
- [ ] Clean
- [ ] Exercise


| Topic | Priority | Progress |
| ----- | -------- | ---------|
| Terraform | 1 | 5% |
| AWS | 1 | 80% |
| Ruby | 1 | 5% |
| Rails | 1 | 15 |
| Docker & Container | 1 | 10% |
| Bash | 1 | 25% |
| Git | 1 | 30% |
