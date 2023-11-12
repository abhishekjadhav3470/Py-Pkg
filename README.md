# Python package

# How to Use this package
```python
from neuron.Perceptron import Perceptron
model = Perceptron(eta=0.3, epochs=10)
```

## reference -

* [Official Python docs for PYPI](https://packaging.python.org/en/latest/tutorials/packaging-projects/)

* [Github action file for PYPI](https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-python#publishing-to-package-registries)

steps to create the API_Token 
1. Create a account in PYPI website and login it later you have verify the account and add the device for verification.
2. Go to account setting and Create a token, it gives a token you have to copy it. it was for only one time use, later it will be vanished.
3. Go to your repo, open setting, you can see the secret option, create a new repo secret, where you have paste the API_token key which was copied and give a name.
4. Give the same which is present in the workflow/publish.yml file, it will added.
5. at last you have to go to the actions, you have already published it, just click on deploy button.

All set!! 

You can see the output at the PYPI in My projects section 

Thanks!!