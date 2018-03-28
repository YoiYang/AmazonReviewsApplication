# Some Applications on Amazon Reviews

These are codes written in Python Jupyter Notebook that work over the review data from Amazon in the musical instrument category.

## Guess Your Score

It uses SVM to learn the relationship between scores and review text, and predict scores given the texts. Overall precision 0.83.

## Amazon Friend Suggestion

It converts the review texts to vectors and calculate the text vectors' cosine similarity between each other. This program identifies the top "friend" pairs that share the most similarity. (Their suggestion tendency goes up if they bought the same item, too)

## Contributing

Please read [CONTRIBUTING.md] for details on our code of conduct, and the process for submitting pull requests to us.

## Authors:

Yang Liu

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Amazon review data: http://jmcauley.ucsd.edu/data/amazon/
* SVM
* Bradley Voytek who taught me basic data science in python
