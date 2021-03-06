
# *Paradigms of Artificial Intelligence Programming* 

![PAIP](https://norvig.com/paip-cover.gif)

# Table of Contents

<ul>
<li>Preface</li>
<li>Why Lisp?  Why Common Lisp?</li>
<li>Outline of the Book</li>
<li>How to use This Book</li>
<li>Supplementary Texts and Reference Books</li>
<li>A Note on Exercises</li>
<li>Acknowledgments</li>
<li><STRONG>Part I  Introduction to Common Lisp</STRONG></li>
<li><STRONG>1  Introduction to Lisp</STRONG></li>
<ul><li>1.1  Symbolic Computation</li>
<li>1.2  Variables</li>
<li>1.3  Special Forms</li>
<li>1.4  Lists</li>
<li>1.5  Defining New Functions</li>
<li>1.6  Using Functions</li>
<li>1.7  Higher-Order Functions</li>
<li>1.8  Other Data Types</li>
<li>1.9  Summary:  The Lisp Evaluation Rule</li>
<li>1.10  What Makes Lisp Different?</li>
<li>1.11  Exercises</li>
<li>1.12  Answers</li></ul>
<li><STRONG>2  A Simple Lisp Program</STRONG></li>
<ul><li>2.1  A Grammar for a Subset of English</li>
<li>2.2  A Straightforward Solution</li>
<li>2.3  A Rule-Based Solution</li>
<li>2.4  Two paths to Follow</li>
<li>2.5  Changing the Grammar without Changing the Program</li>
<li>2.6  Using the Same Data for Several Programs</li>
<li>2.7  Exercises</li>
<li>2.8  Answers</li></ul>
<li><STRONG>3  Overview of Lisp</STRONG></li>
<ul><li>3.1  A Guide to Lisp Style</li>
<li>3.2  Special Forms</li>
<ul><li>Special Forms for Definitions</li>
<li>Special Forms for Conditionals</li>
<li>Special Forms for Dealing with Variables and Places</li>
<li>Functions and Special Forms for Repetition</li>
<li>Repetition through Recursion</li>
<li>Other Special Forms</li>
<li>Macros</li>
<li>Backquote Notation</li></ul>
<li>3.3  Functions on Lists</li>
<li>3.4  Equality and Internal Representation</li>
<li>3.5  Functions on Sequences</li>
<li>3.6  Functions for Maintaining Tables</li>
<li>3.7  Functions on Trees</li>
<li>3.8  Functions on Numbers</li>
<li>3.9  Functions on Sets</li>
<li>3.10  Destructive Functions</li>
<li>3.11 Overview of Data types</li>
<li>3.12  Input/Output</li>
<li>3.13  Debugging tools</li>
<li>3.14  Antibugging Tools</li>
<ul><li>Timing Tools</li></ul>
<li>3.15  Evaluation</li>
<li>3.16  Closures</li>
<li>3.17  Special Variables</li>
<li>3.18  Multiple Values</li>
<li>3.19  More about Parameters</li>
<li>3.20  The Rest of Lisp</li>
<li>3.21  Exercises</li>
<li>3.22  Answers</li></ul>
<li><STRONG>Part II  Early AI Programs</STRONG></li>
<li><STRONG>4  GPS:  The General problem Solver</STRONG></li>
<ul><li>4.1  Stage 1:  Description</li>
<li>4.2  Stage 2:  Specification </li>
<li>4.3  Stage 3:  Implementation</li>
<li>4.4  Stage 4:  Test</li>
<li>4.5  Stage 5:  Analysis, or &quot;We Lied about the G&quot;</li>
<li>4.6  The Running Around the Block Problem</li>
<li>4.7  The Clobbered Sibling Goal Problem</li>
<li>4.8  The Leaping before You Look Problem</li>
<li>4.9  The recursive Subgoal problem</li>
<li>4.10  The Lack of Intermediate Information Problem</li>
<li>4.11  GPS Version 2:  A More General problem Solver</li>
<li>4.12  The New Domain problem:  Monkey and Bananas</li>
<li>4.13  The Maze Searching Domain</li>
<li>4.14  The Blocks World Domain</li>
<ul><li>The Sussman Anomaly</li></ul>
<li>4.15  Stage 5 Repeated:  Analysis of Version 2</li>
<li>4.16  The Not Looking after You Don&#39;t Leap Problem</li>
<li>4.17  The Lack of Descriptive Power Problem</li>
<li>4.18  The Perfect Information Problem</li>
<li>4.19  The Interacting Goals Problem</li>
<li>4.20  The End of GPS</li>
<li>4.21  History and References</li>
<li>4.22 Exercises</li>
<li>4.23  Answers</li></ul>
<li><STRONG>5  Eliza:  Dialog with a Machine</STRONG></li>
<ul><li>5.1  Describing and Specifying Eliza</li>
<li>5.2  Pattern Matching</li>
<li>5.3  Segment Pattern Matching</li>
<li>5.4  The Eliza Program:  A Rule-Based Translator</li>
<li>5.5  History and References</li>
<li>5.6  Exercises</li>
<li>5.7  Answers</li></ul>
<li><STRONG>6  Building Software Tools</STRONG></li>
<ul><li>6.1  An Interactive Interpreter Tool</li>
<li>6.2  A Pattern-Matching Tool</li>
<li>6.3  A Rule-Based Translator Tool</li>
<li>6.4  A Set of Searching Tools</li>
<ul><li>Searching Trees</li>
<li>Guiding the Search</li>
<li>Search Paths</li>
<li>Guessing versus Guaranteeing a Good Solution</li>
<li>Searching Graphs</li></ul>
<li>6.5  GPS as Search</li>
<li>6.6  History and References</li>
<li>6.7  Exercises</li>
<li>6.8  Answers</li></ul>
<li><STRONG>7  Student:  Solving Algebra Word Problems</STRONG></li>
<ul><li>7.1  Translating English into Equations</li>
<li>7.2  Solving Algebraic Equations</li>
<li>7.3  Examples</li>
<li>7.4  History and References</li>
<li>7.5  Exercises</li>
<li>7.6  Answers</li></ul>
<li><STRONG>8  Symbolic Mathematics:  A Simplification Program</STRONG></li>
<ul><li>8.1  Converting Infix to Prefix Notation</li>
<li>8.2  Simplification Rules</li>
<li>8.3  Associativity and Commutativity</li>
<li>8.4  Logs, Trig, and Differentiation</li>
<li>8.5  Limits of Rule-Based Approaches</li>
<li>8.6  Integration</li>
<li>8.7  History and References</li>
<li>8.8. Exercises</li></ul>
<li><STRONG>Part III  Tools and Techniques</STRONG></li>
<li><STRONG>9  Efficiency Issues</STRONG></li>
<ul><li>9.1  Caching Results of Previous Computations:   Memoization</li>
<li>9.2  Compiling One Language into Another</li>
<li>9.3  Delaying Computation</li>
<li>9.4  Indexing Data</li>
<li>9.5  Instrumentation:  Deciding What to Optimize</li>
<li>9.6  A Case Study in Efficiency:  The SIMPLIFY Program</li>
<ul><li>Memoization</li>
<li>Indexing</li>
<li>Compilation</li>
<li>The Single-Rule Compiler</li>
<li>The Rule-Set Compiler</li></ul>
<li>9.7  History and References</li>
<li>9.8  Exercises</li>
<li>9.9  Answers</li></ul>
<li><STRONG>10  Low-Level Efficiency Issues</STRONG></li>
<ul><li>10.1  use Declarations</li>
<li>10.2  Avoid Generic Functions</li>
<li>10.3  Avoid Complex Argument Lists</li>
<li>10.4  Avoid Unnecessary Consing</li>
<ul><li>Avoid Consing:  Unique Lists</li>
<li>Avoid Consing:  Multiple Values</li>
<li>Avoid Consing:  Resources</li></ul>
<li>10.5  Use the Right Data Structures</li>
<ul><li>The Right Data Structure:  Variables</li>
<li>The Right Data Structure:  Queues</li>
<li>The Right Data Structure:  Tables</li></ul>
<li>10.6  Exercises</li>
<li>10.7  Answers</li></ul>
<li><STRONG>11  Logic Programming</STRONG></li>
<ul><li>11.1  Idea 1:  A Uniform Data Base</li>
<li>11.2  Idea 2:  Unification of Logic Variables</li>
<ul><li>Programming with Prolog</li></ul>
<li>11.3  Idea 3:  Automatic Backtracking</li>
<ul><li>Approaches to Backtracking</li>
<li>Anonymous Variables</li></ul>
<li>11.4  The Zebra Puzzle</li>
<li>11.5  The Synergy of Backtracking and Unification</li>
<li>11.6  Destructive Unification</li>
<li>11.7  Prolog in Prolog</li>
<li>11.8  Prolog Compared to Lisp</li>
<li>11.9  History and References</li>
<li>11.10  Exercises</li>
<li>11.11  Answers</li></ul>
<li><STRONG>12  Compiling Logic programs</STRONG></li>
<ul><li>12.1  A prolog Compiler</li>
<li>12.2  Fixing the Errors in the Compiler</li>
<li>12.3  Improving the Compiler</li>
<li>12.4  Improving the Compilation of Unification</li>
<li>12.5  Further Improvements to Unification</li>
<li>12.6  The User Interface to the Compiler</li>
<li>12.7  Benchmarking the Compiler</li>
<li>12.8  Adding More Primitives</li>
<li>12.9  The Cut</li>
<li>12.10  &quot;Real&quot; Prolog</li>
<li>12.11 History and References</li>
<li>12.12  Exercises</li>
<li>12.13  Answers</li></ul>
<li><STRONG>13  Object-Oriented Programming</STRONG></li>
<ul><li>13.1  Object-Oriented Programming</li>
<li>13.2  Objects</li>
<li>13.3  Generic Functions</li>
<li>13.4  Classes</li>
<li>13.5  Delegation</li>
<li>13.6  Inheritance</li>
<li>13.7  CLOS:  The Common Lisp Object System</li>
<li>13.8  A CLOS Example:  Searching Tools</li>
<ul><li>Best-First Search</li></ul>
<li>13.9  Is CLOS Object-Oriented?</li>
<li>13.10  Advantages of Object-Oriented programming</li>
<li>13.11  History and References</li>
<li>13.12  Exercises</li></ul>
<li><STRONG>14  Knowledge Representation and Reasoning</STRONG></li>
<ul><li>14.1  A Taxonomy of Representation Languages</li>
<li>14.2  Predicate Calculus and its Problems</li>
<li>14.3  A Logical Language: Prolog</li>
<li>14.4  Problems with Prolog&#39;s Expressiveness</li>
<li>14.5  Problems with Predicate Calculus&#39;s Expressiveness</li>
<li>14.6  Problems with Completeness</li>
<li>14.7  Problems with Efficiency:  Indexing</li>
<li>14.8  A Solution to the Indexing Problem</li>
<li>14.9  A Solution to the Completeness Problem</li>
<li>14.10  Solutions to the Expressiveness Problems</li>
<ul><li>Higher-Order Predications</li>
<li>Improvements</li>
<li>A Frame Language</li>
<li>Possible Worlds:  Truth, Negation, and Disjunction</li>
<li>Unification, Equality, Types, and Skolem Constants</li></ul>
<li>14.11  History and References</li>
<li>14.12  Exercises</li>
<li>14.13  Answers</li></ul>
<li><STRONG>Part IV  Advanced AI Programs</STRONG></li>
<li><STRONG>15  Symbolic Mathematics with Canonical Forms</STRONG></li>
<ul><li>15.1  A Canonical Form for Polynomials</li>
<li>15.2  Differentiating Polynomials</li>
<li>15.3  Converting between Infix and Prefix</li>
<li>15.4  Benchmarking the Polynomial Simplifier</li>
<li>15.5  A Canonical Form for Rational Expressions</li>
<li>15.6  Extending Rational Expressions</li>
<li>15.7  History and References</li>
<li>15.8  Exercises</li>
<li>15.9  Answers</li></ul>
<li><STRONG>16  Expert Systems</STRONG></li>
<ul><li>16.1  Dealing with Uncertainty</li>
<li>16.2  Caching Derived Facts</li>
<li>16.3  Asking Questions</li>
<li>16.4  Contexts Instead of Variables</li>
<li>16.5  Backward-Chaining Revisited</li>
<li>16.6  Interacting with the Expert</li>
<li>16.7  Interacting with the Client</li>
<li>16.8  MYCIN, A Medical Expert System</li>
<li>16.9  Alternatives to Certainty Factors</li>
<li>16.10  History and References</li>
<li>16.11  Exercises</li>
<li>16.12  Answers</li></ul>
<li><STRONG>17  Line-Diagram Labeling by Constraint Satisfaction</STRONG></li>
<ul><li>17.1  The Line-Labeling Problem</li>
<li>17.2  Combining Constraints and Searching</li>
<li>17.3  Labeling Diagrams</li>
<li>17.4  Checking Diagrams for Errors</li>
<li>17.5  History and References</li>
<li>17.6  Exercises</li></ul>
<li><STRONG>18  Search and the Game of Othello</STRONG></li>
<ul><li>18.1  The Rules of the Game</li>
<li>18.2  Representation Choices</li>
<li>18.3  Evaluating Positions</li>
<li>18.4  Searching Ahead:  Minimax</li>
<li>18.5  Smarter Searching:  Alpha-Beta Search</li>
<li>18.6  An Analysis of Some Games</li>
<li>18.7  The Tournament Version of Othello</li>
<li>18.8  Playing a Series of Games</li>
<li>18.9  More Efficient Searching</li>
<li>18.10  It Pays to Precycle</li>
<li>18.11  Killer Moves</li>
<li>18.12  Championship Programs:  Iago and Bill</li>
<ul><li>Mobility </li>
<li>Edge Stability</li>
<li>Combining the Factors</li></ul>
<li>18.13  Other Techniques</li>
<ul><li>Interative Deepening</li>
<li>Forward Pruning</li>
<li>Nonspeculative Forward Pruning</li>
<li>Aspiration Search</li>
<li>Think-Ahead</li>
<li>Hashing and Opening Book Moves</li>
<li>The End Game</li>
<li>Metareasoning</li>
<li>Learning</li></ul>
<li>18.14  History and References</li>
<li>18.15  Exercises</li>
<li>18.16  Answers</li></ul>
<li><STRONG>19  Introduction to Natural Language</STRONG></li>
<ul><li>19.1  Parsing with a Phrase-Structure Grammar</li>
<li>19.2  Extending the Grammar and Recognizing Ambiguity</li>
<li>19.3  More Efficient parsing</li>
<li>19.4  The Unknown-Word Problem</li>
<li>19.5  Parsing into a Semantic Representation</li>
<li>19.6  Parsing with Preferences</li>
<li>19.7  The Problem with Context-Free Phrase-Structure Rules</li>
<li>19.8  History and References</li>
<li>19.9  Exercises</li>
<li>19.10  Answers</li></ul>
<li><STRONG>20  Unification Grammars</STRONG></li>
<ul><li>20.1  Parsing as Deduction</li>
<li>20.2  Definite Clause Grammars</li>
<li>20.3  A Simple Grammar In DCG Format</li>
<li>20.4  A DCG Grammar with Quantifiers</li>
<li>20.5  Preserving Quantifier Scope Ambiguity</li>
<li>20.6  Long-Distance Dependencies</li>
<li>20.7  Augmenting DCG Rules</li>
<li>20.8  History and References</li>
<li>20.9  Exercises</li>
<li>20.10  Answers</li></ul>
<li><STRONG>21  A Grammar of English</STRONG></li>
<ul><li>21.1  Noun Phrases</li>
<li>21.2  Modifiers</li>
<li>21.3  Noun Modifiers</li>
<li>21.4  Determiners</li>
<li>21.5  Verb Phrases</li>
<li>21.6  Adverbs</li>
<li>21.7  Clauses</li>
<li>21.8  Sentences</li>
<li>21.9  XPs</li>
<li>21.10  Word Categories</li>
<li>21.11  The Lexicon</li>
<ul><li>Verbs</li>
<li>Auxiliary Verbs</li>
<li>Nouns</li>
<li>Pronouns</li>
<li>Names</li>
<li>Adjectives</li>
<li>Adverbs</li>
<li>Articles</li>
<li>Cardinal and Ordinal Numbers</li>
<li>Prepositions</li></ul>
<li>21.12  Supporting the Lexicon</li>
<li>21.13  Other Primitives</li>
<li>21.14  Examples</li>
<li>21.15  History and References</li>
<li>21.16  Exercises</li></ul>
<li><STRONG>Part V  The Rest of Lisp</STRONG></li>
<li><STRONG>22  Scheme:  An Uncommon Lisp</STRONG></li>
<ul><li>22.1  A Scheme Interpreter</li>
<li>22.2  Syntactic Extension with Macros</li>
<li>22.3  A Properly Tail-Recursive Interpreter</li>
<li>22.4  Throw, Catch, and Call/cc</li>
<li>22.5  An interpreter Supporting Call/cc</li>
<li>22.6  History and References</li>
<li>22.7  Exercises</li>
<li>22.8  Answers</li></ul>
<li><STRONG>23  Compiling Lisp</STRONG></li>
<ul><li>23.1  A Properly Tail-Recursive Lisp Compiler</li>
<li>23.2  Introducing Call/cc</li>
<li>23.3  The Abstract Machine</li>
<li>23.4  A Peephole Optimizer</li>
<li>23.5  Languages with Different Lexical Conventions</li>
<li>23.6  History and References</li>
<li>23.7  Exercises</li>
<li>23.8  Answers</li></ul>
<li><STRONG>24  ANSI Common Lisp</STRONG></li>
<ul><li>24.1  Packages</li>
<ul><li>The Seven Name Spaces</li></ul>
<li>24.2  Conditions and Error Handling</li>
<ul><li>Signaling Errors</li>
<li>Handling Errors</li></ul>
<li>24.3  Pretty Printing</li>
<li>24.4  Series</li>
<li>24.5  The Loop Macro</li>
<ul><li>Anatomy of a Loop</li>
<li>Iteration Control (26.6)</li>
<li>End-Test Control (26.7)</li>
<li>Value Accumulation (26.8)</li>
<li>Variable Initialization (26.9)</li>
<li>Conditional Execution (26.10)</li>
<li>Unconditional Execution (26.11)</li>
<li>Miscellaneous Features (26.12)</li></ul>
<li>24.6  Sequence Functions</li>
<ul><li>Once-only:  A Lesson in Macrology</li>
<li>Avoid Overusing Macros</li>
<li>MAP-INTO</li>
<li>REDUCE with :key</li></ul>
<li>24.7  Exercises</li>
<li>24.8  Answers</li></ul>
<li><STRONG>25  Troubleshooting</STRONG></li>
<ul><li>25.1  Nothing Happens</li>
<li>25.2  Change to Variable Has No Effect</li>
<li>25.3  Change to Function Has No Effect</li>
<li>25.4  Values Change &quot;by Themselves&quot;</li>
<li>25.5  Built-In Functions Don&#39;t Find Elements</li>
<li>25.6  Multiple Values Are Lost</li>
<li>25.7  Declarations Are Ignored</li>
<li>25.8  My Lisp Does the Wrong Thing</li>
<li>25.9  How to Find the Function You Want</li>
<li>25.10  Syntax of LOOP</li>
<li>25.11  Syntax of COND</li>
<li>25.12  Syntax of CASE</li>
<li>25.13  Syntax of LET and LET*</li>
<li>25.14  Problems with Macros</li>
<li>25.15  A Style Guide to Lisp</li>
<ul><li>When to Define a Function</li>
<li>When to Define a Special Variable</li>
<li>When to Bind a Lexical Variable</li>
<li>How to Choose a Name</li>
<li>Deciding on the Order of Parameters</li></ul>
<li>25.16  Dealing with Files, Packages, and Systems</li>
<li>25.17  Portability Problems</li>
<li>25.18  Exercises</li>
<li>25.19  Answers</li>
</ul>
<li>Appendix</li>
<li>Bibliography</li>
<li>Index</li></ul></div>
