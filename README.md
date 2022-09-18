# CSS transistions limitations

1. Populates the DOM with all the html elements at all the times, it is just not displayed since the opacity is 0.
   popultaing the dom with alot of elements slows it down.
2. Removing element from DOM animation wont really work if using ternary since react wont scan for any css transistions

# react transistions group

/// behind the scenes you still work with css, but you just have an additional js layer to orchestrate the additon of these key css styles

# react motion

# react move

# react router transition
