# Audio Topics (Modern Media Player)

Next.js (App Router) + Tailwind CSS で構築された、カスタムUIを持つモダンなオーディオプレイヤーです。ローカルの音声ファイルとテキスト（文字起こし）ファイルを読み込み、リッチなダークモード環境で再生・閲覧できるウェブアプリケーションを目指しています。

## ✨ Features

- **ローカルファイル読み込み**: PC内の音声ファイル（mp3, m4a等）とテキストファイル（.txt）をブラウザ上でセキュアに読み込み。
- **モダンなダークUI**: Tailwind CSSを活用した、目に優しいダークモードとすりガラス（Backdrop Blur）風のデザイン。
- **カスタムオーディオコントロール (開発中)**: ブラウザ標準の `<audio>` コントロールを廃止し、Reactの `useRef` と `useState` を用いた完全オリジナルの再生ボタン・シークバーを実装。

## 🛠 Tech Stack

- **Framework**: Next.js (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Lint / Formatting**: ESLint
- **Editor / Environment**: Neovim (ts_ls, tailwindcss-language-server), Windows 11 / WSL Ubuntu

## 🚀 Getting Started

手元の環境で開発サーバーを立ち上げる手順です。

```bash
# パッケージのインストール
npm install

# 開発サーバーの起動
npm run dev
