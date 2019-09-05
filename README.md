## ATM Challenge 

- Basic ATM with account creation, withdrawing, depositing, error messages, cash on hand and all tested with RSpec. 
- Built with Ruby and Rspec. Src found in Gemfile. 


- Big thanks to the entire team.new ("Zak", "Noel", "Angelica")

Running the Program 

Run your IRB

```irb```


Require Date constant

```require "date"```

Load the person.rb file

```load "../lib/person.rb"```

Load atm.rb and account.rb files

```load "../lib/atm.rb"```

```load "../lib/account.rb"```

Running the tests
After you fork the repository, run bundle install in your Terminal and make sure you are in the project folder. That should install RSPEC on your computer.

Then, from your Terminal go to the project folder and run rspec.

Deployment
To create a person, run

```person = Person.new(name: "    ")```

To create an account for a person, run

```person.create_account```

To deposit money on the account of the person, run

```person.deposit(amount)```

To create an ATM, run

```atm = Atm.new```

To withdraw funds, run

```person.withdraw_funds(amount:  , pin:  , atm: atm)```