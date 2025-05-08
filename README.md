```
      ..      .                             
   x88f` `..x88. .>                         
 :8888   xf`*8888%                     u.   
:8888f .888  `"`         uL      ...ue888b  
88888' X8888. >"8x   .ue888Nc..  888R Y888r 
88888  ?88888< 888> d88E`"888E`  888R I888> 
88888   "88888 "8%  888E  888E   888R I888> 
88888 '  `8888>     888E  888E   888R I888> 
`8888> %  X88!      888E  888E  u8888cJ888  
 `888X  `~""`   :   888& .888E   "*888*P"   
   "88k.      .~    *888" 888&     'Y"      
     `""*==~~`       `"   "888E             
                    .dWi   `88E             
                    4888~  J8%              
                     ^"===*"`               
```

# Ego Programming Language

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Difficulty: Extreme](https://img.shields.io/badge/Difficulty-Extreme-red.svg)
![Status: Experimental](https://img.shields.io/badge/Status-Experimental-yellow.svg)

**Ego**: A challenging yet comprehensible esoteric programming language designed to rival Malbolge in difficulty while maintaining readable syntax.

## Warning: Extreme Difficulty

Ego was specifically designed to be one of the most difficult programming languages to master. It uses familiar syntax elements but combines them with complex execution mechanics that will challenge even experienced programmers.

"The most difficult part isn't understanding what you wrote, but predicting what it will do." - *Ego Design Philosophy*

## Triple Context System

What makes Ego uniquely challenging is its **Triple Context Execution Model**:

1. **Primary Context**: What the code literally says
2. **Shadow Context**: Background operations happening in parallel
3. **Meta Context**: How the code modifies itself during execution

Every line of code executes simultaneously in all three contexts, creating complex interactions that are deterministic but extremely difficult to predict.

## Competition with Malbolge

Malbolge, created in 1998 by Ben Olmstead, has long been considered the most difficult programming language to use. It was specifically designed to be nearly impossible to write programs in, with its cryptic syntax, self-encrypting code, and unpredictable behavior. For many years, the challenge of creating a language of comparable difficulty while maintaining any degree of usability seemed insurmountable.

Ego was developed as a direct response to this challenge. Rather than following Malbolge's approach of obfuscation and apparent randomness, Ego takes a fundamentally different path to extreme difficulty:

| Characteristic | Malbolge | Ego |
|----------------|----------|-----|
| **Core Difficulty Source** | Obscure, cryptic syntax and self-encrypting instructions | Complex multi-context interactions with precise synchronization requirements |
| **Syntax Approach** | Deliberately arcane and incomprehensible | Familiar, readable programming constructs |
| **Execution Model** | Single context with encrypted instruction set | Triple context system with quantum variables |
| **Learnability** | Nearly impossible to write programs intentionally | Extremely difficult but systematically learnable |
| **Difficulty Progression** | Immediate and total | Gradual increase as program complexity grows |
| **Self-Modification** | Occurs through encrypted operations | Occurs through explicit transformations across contexts |

Where Malbolge achieves its difficulty through obscurity, Ego achieves comparable difficulty through complexity. This makes Ego a true challenger to Malbolge's status as the most difficult programming language, but with a crucial difference: skilled programmers can, with significant effort, learn to write Ego programs intentionally.

## Key Features

- **Quantum Variables**: Variables exist in superposition states across contexts
- **Context Interference**: Operations create ripple patterns affecting nearby code
- **Enhanced Synchronization**: Code blocks only execute when precise conditions align
- **Context Shifting**: Execution contexts periodically swap roles
- **Variable Entanglement**: Changes to one variable affect others in complex ways
- **Phase Alignment**: Critical operations require contexts to be in phase

## Code Examples

### Hello World in Ego

The following example demonstrates a seemingly simple task - printing "Hello, World!" - that in Ego requires orchestrating all three execution contexts:

```ego
function main() {
    // Quantum variable for the message
    quantum var message = "Hello, World!";
    var index = 0;
    var modifier = 1;
    
    // Create interference pattern
    interfere wave(3, 7, 11);
    
    // Transform statement - modifies how future code behaves
    transform index by [assignment] to modifier;
    
    // Critical phase alignment
    align phases;
    
    loop {
        if(index >= message.length) {
            break;
        }
        
        // This requires precise alignment of all contexts
        sync(index, modifier) {
            display(message[index]);
        }
        
        // Context shift every 4 iterations
        if (index % 4 == 3) {
            shift contexts;
        }
        
        index = index + 1;
        modifier = (modifier * 3) % message.length;
    }
    
    display("@SUCCESS:HELLO_WORLD@");
}
```

The complexity in this seemingly straightforward example comes from:
1. The quantum variable `message` exists differently across contexts
2. The interference pattern created affects how the loop executes
3. The transformation rule modifies how assignments to `index` behave
4. The sync block requires specific mathematical relationships between variables
5. Context shifts rearrange the execution environment periodically

### Fibonacci Sequence

This example calculates the Fibonacci sequence, demonstrating more complex Ego features:

```ego
function fibonacci(int n) {
    // Quantum variables for Fibonacci sequence
    quantum var a = 0;
    quantum var b = 1;
    var count = 0;
    
    // Generate interference pattern
    interfere wave(5, 2, 8);
    
    // Create entanglement between a and b
    entangle(a, b);
    
    // Multiple transformations
    transform a by [addition] to b;
    transform b by [multiplication] to count;
    
    // Phase alignment is critical
    align phases;
    
    while(count < n) {
        // Display is synchronized with complex conditions
        sync(a, b) {
            display(a);
        }
        
        sync(a, b) {
            var temp = a;
            a = b;
            b = temp + b;
        }
        
        count = count + 1;
    }
    
    display("@SUCCESS:FIBONACCI@");
}

function main() {
    fibonacci(10);
}
```

This example demonstrates:
1. Quantum variables used for mathematical calculations
2. Entanglement between variables affecting how they change
3. Multiple transformation rules creating complex interactions
4. Phase alignment required for correct execution
5. Synchronized blocks for both display and variable updates

### Countdown Example

A simpler example showing a countdown from a given number:

```ego
function countdown(int start) {
    // Use quantum variable for more complex behavior
    quantum var i = start;
    var step = 1;
    
    // Create wave interference
    interfere wave(4, 6, 8);
    
    // Transform with multiple patterns
    transform i by [comparison] to step;
    transform step by [assignment] to i;
    
    // Phase alignment
    align phases;
    
    loop {
        // Display with quantum uncertainty
        display(i);
        
        // Entangle variables
        entangle(i, step);
        
        // Multi-condition execution
        sync(i, step) {
            i = i - step;
        }
        
        // Shift contexts periodically
        if (i % 3 == 0) {
            shift contexts;
        }
        
        if(i <= 0) {
            break;
        }
    }
    
    display("@SUCCESS:COUNTDOWN@");
}

function main() {
    countdown(5);
}
```



## The Purpose of Ego

Ego was created to explore a specific question: "Can a language be extraordinarily difficult to program in without resorting to cryptic syntax or random behavior?"

The result is a language that challenges programmers in new ways, emphasizing complex interactions over obscurity, and providing satisfaction when mastered.

## Philosophical Underpinnings

The name "Ego" refers to both the self-referential nature of the language (code that modifies itself) and the Freudian model of the psyche, with its three components (id, ego, superego) mirroring the language's three execution contexts.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Note**: Ego is an experimental language designed for educational and recreational purposes. It is not intended for production use. The extreme difficulty is a feature, not a bug.
