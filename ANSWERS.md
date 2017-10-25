# Q0: Why is this error being thrown?
We haven't made a Pokemon controller yet.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
The .sample method samples a Pokemon and they all have no trainer.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
The line is a button that when clicked, redirects you to the controller action associated with capture_path and parameter @pokemon with a patch method.

# Question 3: What would you name your own Pokemon?
Yo mamaaaaa

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
trainer_path with parameter of @pokemon.trainer

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
I think flash is a Ruby hash and when you fill out flash[:error] it automatically shows an error message. Not really sure about the internal workings of this

# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app
