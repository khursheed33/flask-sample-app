# flask-sample-app
A flask sample App to get started with Flask

<h1> Installation </h1>
    <ul>
    <li>
     <h3>Virtual Environment Setup</h3> 
    </li>
        <ol>
            <li>Install python on your syste</li>
            <li>Install VS Code</li>
            <li>Install Python Extension in VS Code</li>
            <li>`Ctrl+Shift+P` which opens command pallete, then type `Create Environment`</li>
            <li>Select Venv</li>
            <li>Select Python version that you have installed</li>
            <li>Wait untill virtual environment is created. You can see progress in the bottom right corner</li>
            <li>See whether venv is activated or not, to verify see your terminal in the bottom panel it should start with (.venv)</li>
            <li>Follow if virtual environment is not activated</li>
            <li>Reach to the `.venv/Scripts` or `.venv/bin` if Scripts does not exists</li>
            <li>Then run this command => activate</li>

        </ol>
    </ul>

    Run:
        `set FLASK_APP=hello`
        `set FLASK_ENV=development`
        `set FLASK_DEBUG=True`
        `flask --app hello --debug run`


Warning: `Import "flask" could not be resolved`
Fix: `Ctrl+Shift+P` Select Interpreter `Select Python with .venv `
        



