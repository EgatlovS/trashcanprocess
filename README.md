# trashcanprocess

Just played around with some inclusive gateways!

## Inclusive Gateway
> An inclusive gateway may have more than one outgoing sequence flow.
> So n-Tokens may be created for each sequenceflow evaluating true.
> A converging inclusive gateway waits until all tokens arrive.
> !Note!
> Not every Token will be noticed especially if it meats a terminating event before reaching
> the converging inclusive gateway. At this point your process will either wait forever or an 
> exception is thrown.

***

## bpmn model
![trashcanprocess](http://i.imgur.com/tc5HCwE.png)

***

### Stuff used to make this:
 * [camunda modeling reference] (https://camunda.org/bpmn/reference/#gateways-data-based-exclusive-gateways)
 * [camunda docs] (https://docs.camunda.org/manual/7.6/reference/bpmn20/gateways/exclusive-gateway/)
 * [camunda github](https://github.com/camunda/)
 * [camunda modeler](https://camunda.org/download/modeler/)
 * [camunda wildfly distribution](https://camunda.org/download/)
