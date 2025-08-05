# expect-age

> Effortless non-interactive decryption with age
---

## ❓ Why

[age](https://github.com/FiloSottile/age) is a modern encryption tool, but it doesn’t natively support non-interactive password input. **expect-age** bridges this gap, letting you decrypt age-encrypted files automatically—perfect for scripts and automation.

Curious why this is needed? See the discussion [here](https://github.com/FiloSottile/age/discussions/256).

## 🚀 Quick start

First, make sure you have `expect` installed:

```bash
# Debian/Ubuntu
sudo apt install expect

# Arch Linux
sudo pacman -S expect

# Fedora
sudo dnf install expect

# macOS
brew install expect
```

Next, add `expect-age` to your `PATH` and make it executable. Now you can decrypt files non-interactively:

```bash
expect-age "your-password" "/path/to/your/encrypted_file.age" "/path/to/your/decrypted_file.txt"
```

Automate your workflows with ease ⏩!
