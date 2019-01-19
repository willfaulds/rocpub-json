# An example of an extremely simplified proposed data structure (I expect this to be broken and want feedback)
To test the data structure we need to find the most complex/unusual rules and see how they would fit - looking to other rulesets would be advantageous to make this robust.

I’m working along the idea of the data structure being allowed to set the type of logic to be used. The logic would be defined in the code but gives extremely flexibility and future-proofing?

I.e. the logic code has definitions for how to handle the type modifier (simple maths) & subliit (limit an ability score subTotal - i.e. before magic items?)

#Known issues

Someform of "uid" required to avoid duplicate content, and to allow targeting with other logic. Also we need to have a way of storing the exact rules applied to a character... I imagine it being automated at creation where possible.

"source" should perhaps be moved higher up the json chain for efficiency? i.e. top level array.
