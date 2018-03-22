# Q0: Why is this error being thrown?

Since there is no Pokemon model

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *

They are generated. They all belong to the same trainer.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

It creates the button. This button allows the current trainer to capture the pokemon, which invokes the capture method in the pokemon controller.

# Question 3: What would you name your own Pokemon?

Anonymous Pumpkin

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

The path that leads back to the trainer's page.

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

Cannot name the same pokemon multiple times when trying to enter the same pokemon name.

# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app
