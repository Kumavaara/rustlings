# rustlings 🦀❤️

Greetings and welcome to `rustlings`. This project contains solutions for rustlings 5.2 exercises.

## Getting Started

_Note: If you're on MacOS, make sure you've installed Xcode and its developer tools by typing `xcode-select --install`._
_Note: If you're on Linux, make sure you've installed gcc. Deb: `sudo apt install gcc`. Yum: `sudo yum -y install gcc`._

You will need to have Rust installed. You can get it by visiting https://rustup.rs. This'll also install Cargo, Rust's package/project manager.

## MacOS/Linux

Just run:

```bash
curl -L https://raw.githubusercontent.com/rust-lang/rustlings/main/install.sh | bash
# Or if you want it to be installed to a different path:
curl -L https://raw.githubusercontent.com/rust-lang/rustlings/main/install.sh | bash -s mypath/
```

This will install Rustlings and give you access to the `rustlings` command. Run it to get started!

## Windows

In PowerShell (Run as Administrator), set `ExecutionPolicy` to `RemoteSigned`:

```ps1
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

Then, you can run:

```ps1
Start-BitsTransfer -Source https://raw.githubusercontent.com/rust-lang/rustlings/main/install.ps1 -Destination $env:TMP/install_rustlings.ps1; Unblock-File $env:TMP/install_rustlings.ps1; Invoke-Expression $env:TMP/install_rustlings.ps1
```

To install Rustlings. Same as on MacOS/Linux, you will have access to the `rustlings` command after it.

If you get a permission denied message, you might have to exclude the directory where you cloned Rustlings in your antivirus.

## Browser

[Run on Repl.it](https://repl.it/github/rust-lang/rustlings)

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/rust-lang/rustlings)

## Manually

Basically: Clone the repository at the latest tag, run `cargo install --path .`.

```bash
# find out the latest version at https://github.com/rust-lang/rustlings/releases/latest (on edit 5.2.0)
git clone -b 5.2.1 --depth 1 https://github.com/rust-lang/rustlings
cd rustlings
cargo install --force --path .
```

If there are installation errors, ensure that your toolchain is up to date. For the latest, run:

```bash
rustup update
```

Then, same as above, run `rustlings` to get started.

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

Development-focused discussion about Rustlings happens in the [**rustlings** stream](https://rust-lang.zulipchat.com/#narrow/stream/334454-rustlings)
on the [Rust Project Zulip](https://rust-lang.zulipchat.com). Feel free to start a new thread there
if you have ideas or suggestions!

## Contributors ✨

Thanks goes to the wonderful people listed in [AUTHORS.md](./AUTHORS.md) 🎉
