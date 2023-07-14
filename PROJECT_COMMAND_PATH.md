
# new project

## environment

we use vscode on ubuntu

```bash
> code --version 
1.80.1
74f6148eb9ea00507ec113ec51c489d6ffb4b771
x64

> lsb_release -a
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 22.04.2 LTS
Release:        22.04
Codename:       jammy
```

## create project folder and change inside

```bash
 mkdir rust_modules_and_project_structure && cd $_
```

## init cargo bin

```bash
cargo init .
```

## run hello world program inside the vscode console

### open terminal with shortcut

```bash
[Ctrl]+[Shift]+[`]

```

### run cargo

```bash
> cargo run
Finished dev [unoptimized + debuginfo] target(s) in 0.01s
     Running `target/debug/rust_modules_and_project_structure`
Hello, world!
```

Fine works

# open manuel

```bash
export DISPLAY=:0 
echo $DISPLAY
firefox https://dev.to/ghost/rust-project-structure-example-step-by-step-3ee &
```

should open in a browser windows

