# Ruby on Rails full-stack Technical Evaluation

Code quality is very important to us. We're sending you this challenge so that
we can evaluate your coding skills with Ruby.

### What we expect from your code

- Object-oriented
- Clean code
- Consistent style
- Extensibility
- Maintainability
- Testability

# The challenge

- Write code to parse data represented in different formats and normalize to the following format:

  `<first name> <city name> <birth date M/D/YYYY>`

- Users should be able to pick separator and insert several lines of text
- Write at least 2 specs, but no more than 5 - we don't expect 100% coverage

### Instructions

- Use the test framework you're most familiar with
- Use anything you need from Ruby on Rails standard library
- Don't use any gem to accomplish the solution (except test framework)
- Don't worry about invalid input data

### Example code

```
  # Fields: first name, city name, birth date
  * comma:
    'Mckayla, Atlanta, 5/29/1986',
    'Elliot, New York City, 4/3/1947',
  # Fields: city abbreviation, birth date, last name, first name
  * dollar:  
    'LA $ 10-4-1974 $ Nolan $ Rhiannon',
    'NYC $ 12-1-1962 $ Bruen $ Rigoberto'
}

# Expected return (order of entries doesn't matter):
#   Mckayla Atlanta 5/29/1986
#   Elliot New York City 4/3/1947
#   Rhiannon Los Angeles 10/4/1974
#   Rigoberto New York City 12/1/1962

```

# Deliverable

Repo hosted in [GitHub](http://www.github.com). 