# Installation notes

These things are of note when setting up this project.

## Fixing install error for black

If `pipenv install` fails complaining about `black`, then try to do `pipenv lock --pre --clear`

## Virtualenv and jupyter 
Make a jupyter kernel that uses the virtual enivironment Python version made by `pipenv`:

```bash
> pipenv install && pipenv shell
> pip install ipykernel
> ipython kernel install --user --name=KMNIST
> jupyter lab
```

And then select the `KMNIST` kernel from the kernel menu. 
