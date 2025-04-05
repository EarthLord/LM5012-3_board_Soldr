# LM5012/LM5013 regulator board made for Sodlr

## Requirements of the board from Soldr
1. Ideas that are fun and satisfying to build
2. Not trash-bound – ideally something you'd enjoy using or keeping on your desk/shelf
3. Low production cost – target is $1–3 per unit
4. Beginner-friendly – something accessible, even if it’s your first time soldering

## Specs of the board
1. 12V to 100V input to 5V output
  1. Can be down to 6V input if voltage divider for under-voltage lockout is tweaked
  2. 5V output can change also if feedback voltage divider is changed
2. 2.5A maximum output with LM5012 and 3.5A maximum output with LM5013
3. Sub 100uA current drawn at no load

### Soldering experience
The design is made such that different component sizes and soldering gun heat levels are utilized.

1. Both through hole and surface mount components
2. All surface mount components are with larger leads for hand soldering
3. Size varies from a large inductor to 0402 capacitors and resistors for surface mount components
4. Also experience of soldering an exposed pad from the back side for the regulator

## Documentation
The design is documented in the schematic. 
