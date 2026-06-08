<p align="center"><strong>Codexyz CLI</strong> is a fork of OpenAI Codex that runs locally on your computer.
<p align="center">
  <img src="https://github.com/openai/codex/blob/main/.github/codex-cli-splash.png" alt="Codexyz CLI splash" width="80%" />
</p>
</br>
If you want Codex in your code editor (VS Code, Cursor, Windsurf), <a href="https://developers.openai.com/codex/ide">install in your IDE.</a>
</br>If you want the desktop app experience, run <code>codexyz app</code> or visit <a href="https://chatgpt.com/codex?app-landing-page=true">the Codex App page</a>.
</br>If you are looking for the <em>cloud-based agent</em> from OpenAI, <strong>Codex Web</strong>, go to <a href="https://chatgpt.com/codex">chatgpt.com/codex</a>.</p>

---

## Quickstart

### Installing and running Codexyz CLI

Run the following on Mac or Linux to install Codexyz CLI:

```shell
curl -fsSL https://github.com/StackKnight/codexyz/releases/latest/download/install.sh | sh
```

Run the following on Windows to install Codexyz CLI:

```
powershell -ExecutionPolicy ByPass -c "irm https://github.com/StackKnight/codexyz/releases/latest/download/install.ps1 | iex"
```

Codexyz CLI can also be installed via the following package managers:

```shell
# Install using npm
npm install -g codexyz
```

```shell
# Install using Homebrew
brew install --cask codexyz
```

Then simply run `codexyz` to get started.

<details>
<summary>You can also go to the <a href="https://github.com/StackKnight/codexyz/releases/latest">latest GitHub Release</a> and download the appropriate binary for your platform.</summary>

Each GitHub Release contains many executables, but in practice, you likely want one of these:

- macOS
  - Apple Silicon/arm64: `codexyz-aarch64-apple-darwin.tar.gz`
  - x86_64 (older Mac hardware): `codexyz-x86_64-apple-darwin.tar.gz`
- Linux
  - x86_64: `codexyz-x86_64-unknown-linux-musl.tar.gz`
  - arm64: `codexyz-aarch64-unknown-linux-musl.tar.gz`

Each archive contains a single entry with the platform baked into the name (e.g., `codexyz-x86_64-unknown-linux-musl`), so you likely want to rename it to `codexyz` after extracting it.

</details>

### Using Codexyz with your ChatGPT plan

Run `codexyz` and select **Sign in with ChatGPT**. We recommend signing into your ChatGPT account to use Codexyz as part of your Plus, Pro, Business, Edu, or Enterprise plan. [Learn more about what's included in your ChatGPT plan](https://help.openai.com/en/articles/11369540-codex-in-chatgpt).

You can also use Codexyz with an API key, but this requires [additional setup](https://developers.openai.com/codex/auth#sign-in-with-an-api-key).

## Docs

- [**Codex Documentation**](https://developers.openai.com/codex)
- [**Contributing**](./docs/contributing.md)
- [**Installing & building**](./docs/install.md)
- [**Open source fund**](./docs/open-source-fund.md)

This repository is licensed under the [Apache-2.0 License](LICENSE).
