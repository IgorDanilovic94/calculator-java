# calculator-java
simple calculator written in Java; supports addition, subtraction, multiplication and division

LOC report for caluclator.java - 188 number of code lines
LOC report for start.java - 26 number of code lines

![image](https://github.com/IgorDanilovic94/calculator-java/assets/96244886/b6c9aa24-f07e-4127-814c-45118147c7c3)
![image](https://github.com/IgorDanilovic94/calculator-java/assets/96244886/5d60c3f7-3578-4578-a0bd-d6bf0c1eb8ef)
![image](https://github.com/IgorDanilovic94/calculator-java/assets/96244886/2298dadd-15f8-4921-8b1c-dab67356258c)

Caluclator.java:
line 4. - "Add a private constructor to hide the implicit public one."
line 18. - "String Calculator.Operations.ToString()
Rename method "ToString" to prevent any misunderstanding/clash with method "toString" defined in superclass "java.lang.Object".sonarlint(java:S1845)
Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.sonarlint(java:S100)"
line 24. - "String Calculator.Run(String expression)
Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.sonarlint(java:S100)"
line 183. - "Remove this redundant jump.sonarlint(java:S3626)"

Start.java:
line 6. - "String Expression - Start.main(String[])
Rename this local variable to match the regular expression '^[a-z][a-zA-Z0-9]*$'.sonarlint(java:S117)"
line 8. and 19. - "java.lang.System - Replace this use of System.out or System.err by a logger.sonarlint(java:S106)"

