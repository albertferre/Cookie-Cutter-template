ENVNAME = {{cookiecutter.repo_name}}

install:
	@echo "Installing..."
	conda create -n $(ENVNAME) python={{cookiecutter.python_version}} -y
	call conda activate $(ENVNAME) && pip install -r requirements.txt && pip install pre-commit
