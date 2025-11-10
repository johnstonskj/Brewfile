## ====================================================================================================================
## Layer 00 => Bootstrap
## ====================================================================================================================

# Tap homebrew itself
tap 'homebrew/cask'
tap 'homebrew/cask-drivers'
tap 'homebrew/cask-fonts'
tap 'homebrew/cask-versions'
tap 'homebrew/core'
tap 'homebrew/boneyard'
tap 'homebrew/dev-tools'
tap 'homebrew/bundle'
tap 'homebrew/services'

tap  'rcmdnk/file'
brew 'brew-file'

brew 'mas'

## ====================================================================================================================
## Layer 01 ❱ Basic Shell Environment
## ====================================================================================================================

# Bash is the Bourne Again SHell. Bash is an sh-compatible shell.
brew 'bash'

# Programmable completion functions for bash
brew 'bash-completion'

# Zsh is a shell designed for interactive use.
brew 'zsh'

# A plugin for zsh to make your command line life much easier.
brew 'zsh-syntax-highlighting'

# Another really helpful zsh plugin.
brew 'zsh-autosuggestion'

# Cross-shell prompt
brew 'starship'

# GPU-based terminal emulator
cask 'kitty'

# ---------------------------------------------------------------------------------------------------------------------
# Layer 01 ❱ Basic Shell Environment ❱ GNU Utilities
# ---------------------------------------------------------------------------------------------------------------------

# Basic file, shell and text manipulation utilities of the GNU operating system.
brew 'coreutils'

brew 'binutils'
brew 'diffutils'
brew 'ed'
brew 'findutils'
brew 'gawk'
brew 'gnu-indent'
brew 'gnu-sed'
brew 'gnu-tar'
brew 'gnu-which'
brew 'gnutls'
brew 'gzip'
brew 'inetutils'
brew 'watch'
brew 'wdiff'

brew 'gdb'  # gdb requires further actions to make it work. See `brew info gdb`.
brew 'gpatch'
brew 'm4'
brew 'make'
brew 'nano'

# Automake is a tool for automatically generating Makefile installation files.
brew 'automake'

# GNU Privacy Guard (GnuPG) provides encryption as a free replacement for PGP.
brew 'gpg'

# GNU Privacy Guard (GnuPG) PIN entry for macOS to do GPG terminal decryption
brew 'pinentry-mac'

# ---------------------------------------------------------------------------------------------------------------------
# Layer 01 ❱ Basic Shell Environment ❱ Better Utilities
# ---------------------------------------------------------------------------------------------------------------------

# bat is like `cat` plus line numbers, syntax highlighting, and more.
brew 'bat'

# less is like `more` plus has more capability.
brew 'less'

# curl is a command line tool for transferring data with URL syntax.
brew 'curl', link: true

# Wget is a free software package for retrieving files using HTTP and FTP.
brew 'wget'

# Zstandard is the best modern compression
brew 'zstd'

# bcrypt is high quality encryption that is very popular
brew 'bcrypt'

# scrypt is high quality encryption
brew 'scrypt'

# Pass, a Unix password manager for the command line
brew 'pass'

# rsync is the classic unix file synchronizer.
brew 'rsync'

# Unison is a high-level file synchronization utility.
brew 'unison'

# ripgrep is text search; we prefer it over grep, ag, git grep, ucg, pt, sift.
brew 'ripgrep'

# OpenSSL is an open-source implementation of the SSL and TLS protocols.
brew 'openssl'

# fd: a simple, fast and user-friendly alternative to find.
brew 'fd'

# The `z` command to `cd` among directories.
brew 'zoxide'

# jq is a lightweight and flexible command-line JSON processor.
brew 'jq'

# yq is a lightweight and flexible command-line YAML processor.
brew 'yq'

# xsv is for CSV file parsing, and is fast, full featured, and flexible.
brew 'xsv'

# Tad is CSV viewer with features for pivot, search, etc.
cask 'tad'

# TODO
brew 'imagemagick'

# GraphicsMagick is the swiss army knife of image processing.
brew 'graphicsmagick'

# TODO
brew 'graphviz'

# Gnuplot is a portable command-line driven graphing utility.
brew 'gnuplot'

# Visualization Toolkit for manipulating and displaying scientific data
brew 'vtk'

# ---------------------------------------------------------------------------------------------------------------------
# Layer 01 ❱ Basic Shell Environment ❱ Editors
# ---------------------------------------------------------------------------------------------------------------------

# MacVIM editor
cask 'macvim'
cask 'neovim'

# Emacs editor with extra features; recommended by Spacemacs and Doom emacs
brew 'emacs-plus'

# MacDown simple markdown editor
cask 'macdown'

# MacTex: LaTeX document preparation system with high-quality typesetting.
cask 'mactex'

# Pandoc document convert
brew 'pandoc', link: true

# Spell check
brew 'aspell'

## ====================================================================================================================
## Layer 02 => System Integration
## ====================================================================================================================

# Application launcher and productivity software
cask 'alfred'

# Cable-free audio router
cask 'loopback'

# Sound and audio controller
cask 'soundsource'

# Used to access context-specific actions when text is selected
cask 'popclip'

# The Launchpad Replacement macOS 26 Deserves
cask 'launchie'

# Multi-cloud backup application
cask 'arq'

# Mac OS Quick-Look Plugins
cask 'qlcolorcode'    # QL for code with highlighting
cask 'qlimagesize'    # QL for size info for images
cask 'qlmarkdown'     # QL for markdown files
cask 'qlprettypatch'  # QL for patch / diff files
cask 'qlstephen'      # QL for dev text files
cask 'qlvideo'        # QL for video formats
cask 'quicklook-csv'  # QL for tables in CSV format
cask 'quicklook-json', args: { require_sha: false } # QL for JSON, with trees
cask 'webpquicklook',  args: { require_sha: false } # QL for WebP image files

# ---------------------------------------------------------------------------------------------------------------------
# Layer 02 => System Integration ❱ Fonts
# ---------------------------------------------------------------------------------------------------------------------

brew 'font-fira-code'
brew 'font-fira-code-nerd-font'
brew 'font-fira-mono'
brew 'font-fira-mono-nerd-font'
brew 'font-fira-mono-for-powerline'
brew 'font-fira-sans'
brew 'font-fira-sans-condensed'
brew 'font-fira-sans-extra-condensed'
cask 'font-hack'
cask 'font-inconsolata'
cask 'font-meslo-lg-nerd-font'

## ====================================================================================================================
## Layer 03 => General-Purpose Productivity
## ====================================================================================================================

cask 'adobe-creative-cloud'

# Google Chrome web browser
cask 'google-chrome'

# Slack chat client
cask 'slack'

# Microsof Office is a large suite of software for documents, spreadsheets, diagrams.
cask 'microsoft-office'

# Anthropic's official Claude AI desktop app
cask 'claude'

## ====================================================================================================================
## Layer 04 => Development Tools
## ====================================================================================================================

# Git is a free and open source distributed version control system.
brew 'git'

# Git Large File Storage
brew 'git-lfs'

# Small git utilities
brew 'git-extras'

# Transparent encryption for git repos
brew 'git-crypt'

# Text-mode interface for git repositories
brew 'tig'

# Github command-line interface
brew 'gh'

# Load/unload environment variables based on $PWD
brew 'direnv'

brew 'plantuml'

# Shell script syntax check linter
brew 'shellcheck'

# CLI for GitKraken
cask 'gitkraken-cli'

# Source code line counter
brew 'tokei'

# Polyglot runtime manager (asdf rust clone)
brew 'mise'

# Charles: enables a developer to view HTTP traffic.
# cask 'charles'

# Postman: a complete API Development Environment.
# cask 'postman'

# Insomnia: REST client for API testing.
# cask 'insomnia'

# Xquartz X.Org X Window System that runs on OS X; needed for some image software.
cask 'xquartz'

# ---------------------------------------------------------------------------------------------------------------------
# Layer 04 => Development Tools ❱ Libraries & Frameworks
# ---------------------------------------------------------------------------------------------------------------------

# ---------------------------------------------------------------------------------------------------------------------
# Layer 04 => Development Tools ❱ Programming Languages
# ---------------------------------------------------------------------------------------------------------------------

# GCC GNU Compiler Collection
brew 'gcc'

# LLVM compiler
brew 'llvm', args: ['with-toolchain']

# GNU CLISP, a Common Lisp implementation
brew 'clisp'

# GNU Ubiquitous Intelligent Language for Extensions
brew 'guile'
brew 'guile-fibers'
brew 'guile-gnutls'

# Node.js is a JavaScript platform for building fast, scalable network app.
brew 'node'

# V8 JavaScript Engine.
brew 'v8'

# Switching node versions
brew 'nvm'

# OCaml: General purpose programming language in the ML family
brew 'ocaml'
brew 'ocaml-findlib'
brew 'ocaml-zarith'
brew 'ocamlbuild'
brew 'opam'

# Python programming language, esp. for systems scripting.
brew 'python3'

# Ruby programming language; compare `perl`, `python`.
brew 'ruby'

# Rust!!!!
brew 'rustup'

# Modern programming language in the Lisp/Scheme family
cask "racket"

# A variety of scheme implementations
brew 'chezscheme'
# brew 'chibi-scheme'
# brew 'gambit-scheme'
# brew 'gerbil-scheme'
# brew 'mit-scheme'
# brew 'sagittarius-scheme'
# brew 'scheme48'
# brew 'sisc-scheme'

# Tool to help with Swift style and conventions.
brew 'swiftlint'

# YAML lint validator
brew 'yamllint'

# ---------------------------------------------------------------------------------------------------------------------
# Layer 04 => Development Tools ❱ IDE & Agents
# ---------------------------------------------------------------------------------------------------------------------

# Visual Studio Code editor
cask 'visual-studio-code'

# Xcode, full installation
mas 'Xcode', id: 497799835

# Alcatraz Xcode plugin manager
cask 'alcatraz'

# Carthage Xcode project dependency manager.
brew 'carthage'

# Terminal-based AI coding assistant
cask "claude-code"
cask "claude-cmd"
cask "claude-hooks"
cask "claudekit"

# Finder extension to use Git
# mas 'SnailGit – Git for Finder', id: 847260112

# ---------------------------------------------------------------------------------------------------------------------
# Layer 04 => Development Tools ❱ Runtime
# ---------------------------------------------------------------------------------------------------------------------

# SQLite database: self-contained, serverless, zero-configuration, transactional engine.
brew 'sqlite', link: true

# ZeroMQ message queue
# brew 'zeromq'

## ====================================================================================================================
## Layer 05 => Personal Apps
## ====================================================================================================================

# Diagramming
cask 'omnigraffle'

# Track money & budgets
mas 'Copilot: Track & Budget Money', id: 1447330651

# The best dive logger
mas 'DiveLogDT', id: 411603212

# Simple CAS for Mac
mas 'MathStudio', id: 829912893

# Proton suite of privacy-focused apps
# brew 'proton-drive'
# brew 'proton-mail'
# brew 'proton-pass'
# brew 'protonvpn'