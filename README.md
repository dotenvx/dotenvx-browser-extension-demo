> [!IMPORTANT]
>
> This is a demo repo for purposes of the chrome extensions team to review the dotenvx chrome extension.
>
> dotenvx-browser-extension-demo

## Usage

### Success Path

1. Browse to [`.env.keys`](https://github.com/dotenvx/dotenvx-browser-extension-demo/blob/main/.env.keys#L7)
2. Copy `DOTENV_PRIVATE_KEY` value `2c6cbf0c8b754d974a8001c5527fb47a38d418bd86bcb74ca40c42e650eba80a`
3. Visit [`.env`](https://github.com/dotenvx/dotenvx-browser-extension-demo/blob/main/.env)
4. With the dotenvx chrome extension installed, you'll note that the `encrypted:*` values are visible different
5. Click `decrypt` toward the top-right corner of the file view inside GitHub.
6. You will be prompted to enter the `DOTENV_PRIVATE_KEY`
7. Paste in `2c6cbf0c8b754d974a8001c5527fb47a38d418bd86bcb74ca40c42e650eba80a` and click Save
8. Click `decrypt` at top-right again.
9. Your values will be successfully decrypted.

### Error Path

Do much of the same above, but enter in an invalid private decryption key like `3e0d01c979869f5fe178616d265c902cb1ac47cc85fdb9942c04b0e26cc4269d`.

Attempt to click `decrypt` and you will be presented with a decryption related error.

---

Thank you for testing our chrome extension. 🙏
