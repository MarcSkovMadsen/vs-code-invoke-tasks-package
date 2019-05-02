# vs-code-invoke-tasks-package

This is an example of an Invoke tasks package. See http://docs.pyinvoke.org/en/1.2/concepts/namespaces.html#importing-modules-as-collections.

It's used to discuss how to improve the vs code Invoke extension. See https://marketplace.visualstudio.com/items?itemName=dchanco.vsc-invoke&amp;ssr=false#qna

## Gettings Started

Clone the repo

```bash
git clone https://github.com/MarcSkovMadsen/vs-code-invoke-tasks-package.git
```

Move into the root folder

```bash
cd vs-code-invoke-tasks-package
```

Create a virtual environment and activate it. I use *virtualenv* and the *git bash* terminal on Windows. Feel to use your favourite methodology and technology.

```bash
virtualenv .venv
source .venv/Scripts/activate
```

Install Invoke.

```bash
pip install pyinvoke
```

You can now test the installation by running

```bash
invoke --list
```

and

```bash
$ invoke hello.world
Hello World
```

and

```bash
$ invoke world.hello
World Hello
```