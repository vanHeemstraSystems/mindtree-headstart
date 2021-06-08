mindtree-headstart
# Mindtree - Headstart

Based on "Mindtree" at https://github.com/skitsanos/mindtree

# mindtree
Declarative mind mapping

![mindtree-screenshot](https://user-images.githubusercontent.com/12828104/121186824-c2c7e900-c867-11eb-8b76-cabe01322875.png)

### Building the Mindtree

Grab latest sources:

```sh
$ git clone https://github.com/vanHeemstraSystems/mindtree-headstart.git
```

Optionally, to not use certificates:

```sh
$ npm config set strict-ssl false
```

Install dependencies

```sh
$ cd mindtree
$ npm install
```

Build

```sh
$ npm run-script build
```

### Writing mind maps

```yaml
My Project:
- []:
  - name: task1
    notes: Some task notes written here....
  - name: task2
  - name: task3
    []:
      - name: Level 2 task.1
      - name: Level 2 task.2
        []:
        - name: Level 3 task.1
        - name: Level 3 task.2
      
```
