# use_case3_completion_style

## Purpose
Demonstrates attacks that steer how the model completes a response rather than what task it performs.

## Example Injection
$(System.Collections.Hashtable.Example)

## Risk Note
Medium risk because style guidance can still alter safety and disclosure behavior.

## Files
- Program.cs prints the scenario summary and calculated risk score.
- Calculator.cs defines the scenario model and the scoring logic.
- CalculatorTests.cs contains simple validation helpers for the scenario.
