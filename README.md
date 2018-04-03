Scope defined how memory is accessed/allocated. Varialbles in global scope is available anywhere in the code. Local variables are only available within a scope/block of code.

global variables are usually avoided because they stay the whole time the application is running. They can also be modified unintentionally causing bugs or uninteded side effects.

Strict mode prevents declaring variables withouth the key words 'const', 'let' or 'var' which helps prevent accidentally creating global variables.

Side effects are unintentional changes in your programs functionality caused by scope. A pure function is a function that returns with the same value if it's provided with the same input every time and it has no side effects.