## Requirements

The following are the dependencies listed in the `app/backend/requirements.txt` file:

```
# Example content of requirements.txt
flask==2.0.1
requests==2.25.1
pandas==1.3.3
numpy==1.21.2
scikit-learn==0.24.2
```

Make sure to install these dependencies using the following command:

```sh
pip install -r requirements.txt
```

## Running the Application

To run the application, navigate to the `app/backend` directory and execute the following command:

```sh
python app.py
```

This will start the backend server, and you should see output indicating that the server is running.

## Testing the Application

To test the application, you can use tools like `curl` or Postman to send requests to the server. For example, to test the root endpoint, you can use:

```sh
curl http://localhost:5000/
```

You should receive a response from the server indicating that it is working correctly.

## Additional Resources

For more information on the dependencies and how to use them, refer to the following documentation:

- [Flask Documentation](https://flask.palletsprojects.com/)
- [Requests Documentation](https://docs.python-requests.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [NumPy Documentation](https://numpy.org/)
- [Scikit-learn Documentation](https://scikit-learn.org/)