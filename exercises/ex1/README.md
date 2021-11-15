# INT360 - Apply Machine Learning and Regression Models to Classify Data Records

<!-- toc -->

* [Exercise 01](#exercise-01)
  * [Executing the Jupyter Notebook](#executing-the-jupyter-notebook)
    * [Executing the Notebook directly in the browser](#executing-the-notebook-directly-in-the-browser)
    * [Executing the Notebook locally](#executing-the-notebook-locally)

<!-- Regenerate with "pre-commit run -a markdown-toc" -->

<!-- tocstop -->

## Exercise 01

The first exercise will introduce you to a new feature in Data Attribute Recommendation:
the newly added model template for regression. In this exercise, we will leverage the Python SDK
for Data Attribute Recommendation to predict prices for products based on product attributes.

*Make sure you have fulfilled the prerequisites listed in the main [README](/README.md).*

The exercise is realized as a [Jupyter notebook](./Data_Attribute_Recommendation_Regression_Model_Template.ipynb).

### Executing the Jupyter Notebook

There are two options: running the notebook locally or running it on a cloud service.

#### Executing the Notebook directly in the browser

The easiest way to get started with Jupyter is to launch the
notebook directly in your browser via [mybinder.org].

[mybinder.org]: https://mybinder.org/v2/gh/SAP-samples/teched2021-INT360/main?filepath=exercises%2Fex1%2FData_Attribute_Recommendation_Regression_Model_Template.ipynb

It may take up to five minutes to launch the notebook. Sessions on this free service
can be terminated after a [10 minutes of inactivity]. Make sure not to leave the
browser window for long periods of time and download your notebook once you
are done with the workshop for safekeeping.

[10 minutes of inactivity]: https://mybinder.readthedocs.io/en/latest/about/about.html#how-long-will-my-binder-session-last

If the main link above does not work for you and the notebook is not launching
even after five minutes, you can directly try one of the
[fallback options](https://binderhub.readthedocs.io/en/stable/federation/federation.html):
[Binderhub], [OVH] or [GESIS].

[Binderhub]: https://gke.mybinder.org/v2/gh/SAP-samples/teched2021-INT360/main?filepath=exercises%2Fex1%2FData_Attribute_Recommendation_Regression_Model_Template.ipynb
[OVH]: https://ovh.mybinder.org/v2/gh/SAP-samples/teched2021-INT360/main?filepath=exercises%2Fex1%2FData_Attribute_Recommendation_Regression_Model_Template.ipynb
[GESIS]: https://notebooks.gesis.org/binder/v2/gh/SAP-samples/teched2021-INT360/main?filepath=exercises%2Fex1%2FData_Attribute_Recommendation_Regression_Model_Template.ipynb

If you prefer, the notebook is also available on [Google Colab] after prior login.

[Google Colab]: https://colab.research.google.com/github/SAP-samples/teched2021-INT360/blob/main/exercises/ex1/Data_Attribute_Recommendation_Regression_Model_Template.ipynb

**Using the mybinder.org service or the Google Colab service is completely voluntary
and you are responsible for any information that you may add to mybinder.org. The
reference to the mybinder.org and Google Colab services are not an endorsement of
the respective offerings. You will be subject
to the terms and conditions and to the privacy policy of the respective offerings.**

Once you have launched the notebook, you are all set.
The remaining workshop content is located inside the notebook.

#### Executing the Notebook locally

If you prefer to run the notebook locally, we have a separate set of instructions
for a [Docker-based setup].

[Docker-based setup]: /exercises/ex1/docs/markdown/running_docker_locally.md
