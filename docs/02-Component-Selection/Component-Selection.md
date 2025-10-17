---
title: Component Selection
---


**Op Amps**

1. MCP6004-I/P-ND surface mount crystal

    ![](part1.png)

    * $0.59/each
    * [link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060?gclsrc=aw.ds&gad_source=1&gad_campaignid=120565755&gbraid=0AAAAADrbLlgvmi-7nu49IK00wDfqUZ9nG&gclid=CjwKCAjwr8LHBhBKEiwAy47uUg2Khy4UAju_plOeBhHjGhTL9rCemC6lQ3zkZeHUy87t1d8vDi-Z9BoCKtUQAvD_BwE)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | likely way to many pins then needed |
    | Already have the part on hand             | takes up a significant amount of space                                        |
    | Familiar with the part |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
