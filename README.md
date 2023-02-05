# Topsis_102003448

<H1>Topsis Package</H1>

Welcome to the Topsis Package, a Python library for implementing the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) method. TOPSIS is a multicriteria decision making (MCDM) method used to evaluate and compare alternatives based on multiple criteria.

Installation<br>
The Topsis Package can be installed via pip:

pip install Topsis-102003448
Usage<br>
Using the Topsis Package is straightforward. First, import the package:

<ul>from topsis import Topsis</ul><br>
Next, create an instance of the Topsis class, passing in a list of alternatives, a list of criteria, and a list of weights:


topsis = Topsis(alternatives, criteria, weights)
Finally, call the calculate method to get the results:

The results will be a dictionary with two keys: scores and ranking. The scores key will contain a list of the relative closeness values for each alternative, and the ranking key will contain a list of the alternatives ranked in order of preference.

Deployment on PyPI<br>
The Topsis Package is deployed on PyPI, the Python Package Index. This means that it can be easily installed using pip, as described above.

Conclusion<br>
I hope that you find the Topsis Package useful. If you have any questions, comments, or feedback, please don't hesitate to reach out.
