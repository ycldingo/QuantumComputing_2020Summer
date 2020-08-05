# Instruction

## Prerequisite

Before running the code, please make sure that you have already install `qiskit` package and is running the pregram under the environment of that.

- `apitoken`:

Please create an IBM Quantum Experience account. 
You can find your own API Token under 'My Account / Qiskit in local environment'.
Copy it and paste at
```python
apitoken = 'paste your api token here'
```

- `IBMQ_get_provider`:

For those free account, you need to replace the last line with
```python
provider = IBMQ.get_provider(project='main')
```

- Please **run the notebook from the very first cell**. Otherwise, you may encounter some warnings or errors due to undefined parameters or un-import packages.


## Plot quantum circuits

- `matplotlib`:

  For those who want to plot circuits with `output='mpl'`, remember to install package `matplotlib`. 
  1. Open Anaconda prompt and run
  ```javascript
  conda activate IBMQ
  ```
    to go to the right environment. `IBMQ` is the customized name of your environment.
  
  2. Install package
  ```javascript
  pip install matplotlib
  ```
  
  3. Done.

The default output is `output=text`. 
Note that some functions may nor support this output. We suggest you to change to the default setting if there is any error.
  

