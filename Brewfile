## ====================================================================================================================
## Layer 00 => Bootstrap
## ====================================================================================================================

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
brew 'zsh-autosuggestions'

# For better argument parsing in shell scripts
brew 'gnu-getopt'

# Cross-shell prompt
brew 'starship'

# GPU-based terminal emulator
cask 'kitty'

# Terminal multiplexer
brew 'tmux'

# Manage complex tmux sessions easily
brew 'tmuxinator'

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

# rsync is the classic unix file synchronizer.
brew 'rsync'

# Unison is a high-level file synchronization utility.
brew 'unison'

# ripgrep is text search; we prefer it over grep, ag, git grep, ucg, pt, sift.
brew 'ripgrep'

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
# Layer 01 ❱ Basic Shell Environment ❱ Security-Related
# ---------------------------------------------------------------------------------------------------------------------

# Pass, a Unix password manager for the command line
brew 'pass'

# bcrypt is high quality encryption that is very popular
brew 'bcrypt'

# scrypt is high quality encryption
brew 'scrypt'

# OpenSSL is an open-source implementation of the SSL and TLS protocols.
brew 'openssl'

# GNU Privacy Guard (GnuPG) provides encryption as a free replacement for PGP.
brew 'gpg'

# GNU Privacy Guard (GnuPG) PIN entry for macOS to do GPG terminal decryption
brew 'pinentry-mac'

brew 'gpg-tui'

cask 'gpgfrontend'

# ---------------------------------------------------------------------------------------------------------------------
# Layer 01 ❱ Basic Shell Environment ❱ Editors
# ---------------------------------------------------------------------------------------------------------------------

# GUI for vim, made for macOS
cask 'macvim-app'

# Ambitious Vim-fork focused on extensibility and agility
brew 'neovim'

tap 'd12frosted/emacs-plus'

# Emacs editor with extra features; recommended by Spacemacs and Doom emacs
brew 'emacs-plus@29', args: ['with-native-comp', 'with-imagemagick', 'with-dbus', 'with-ctags']

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

# A better console tool
cask 'console'

# Application launcher and productivity software
cask 'alfred', adopt: true

# Cable-free audio router
cask 'loopback'

# Sound and audio controller
cask 'soundsource'

# Used to access context-specific actions when text is selected
cask 'popclip'

# The Launchpad Replacement macOS 26 Deserves
mas 'Launchie App Launcher', id: 6752657468

# Google Drive client for Mac
cask 'google-drive'

# 1Password password manager
cask '1password', adopt: true
# Multi-cloud backup application
cask 'arq'

# Mac OS Quick-Look Plugins
cask 'qlcolorcode'    # QL for code with highlighting
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

cask 'font-fira-code'
cask 'font-fira-code-nerd-font'
cask 'font-fira-mono'
cask 'font-fira-mono-nerd-font'
cask 'font-fira-mono-for-powerline'
cask 'font-fira-sans'
cask 'font-fira-sans-condensed'
cask 'font-fira-sans-extra-condensed'
cask 'font-hack'
cask 'font-inconsolata'
cask 'font-meslo-lg'
cask 'font-meslo-lg-nerd-font'
cask 'font-linux-libertine'

## ====================================================================================================================
## Layer 03 => General-Purpose Productivity
## ====================================================================================================================

# Browser & Social
cask 'google-chrome'
# cask 'firefox'
# cask 'brave-browser'

# Communication clients
cask 'slack', adopt: true
cask 'zoom', adopt: true
cask 'signal'
cask 'messenger'
cask 'whatsapp'

# Client to install Adobe apps
cask 'adobe-creative-cloud'

mas 'PDF Expert – Edit, Sign PDFs', id: 1055273043

# Microsof Office is a large suite of software for documents, spreadsheets, diagrams.
cask 'microsoft-office'

# Proton suite of privacy-focused apps
cask 'proton-drive', adopt: true
cask 'proton-mail', adopt: true
cask 'proton-pass', adopt: true
cask 'protonvpn', adopt: true
cask 'standard-notes', adopt: true

mas 'Proton Pass for Safari', id: 6502835663

# Damn fine LaTeX editor
cask 'texifier'

# Diagramming
cask 'omnigraffle', adopt: true

# Simple CAS for Mac
mas 'MathStudio', id: 829912893

# Anthropic's official Claude AI desktop app
cask 'claude', adopt: true

# Finder/Menubar extensions
mas 'Meeting Reminder In Your Face', id: 1476964367
mas 'Plock • Pop-up Clock', id: 1642528649

# Utilities
mas 'Cicero: A Unicode® Tool', id: 1480977453
mas 'Ultra Character Map', id: 520265986

## ====================================================================================================================
## Layer 04 => Development Tools
## ====================================================================================================================

# Git is a free and open source distributed version control system.
brew 'git'
brew 'git-lfs'
brew 'git-extras'
brew 'git-crypt'
brew 'tig'
cask 'gitkraken-cli'

# Github command-line interface
brew 'gh'

# Load/unload environment variables based on $PWD
brew 'direnv'

brew 'plantuml'

# Shell script syntax check linter
brew 'shellcheck'

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

# No longer used; kept for reference

# Settings repository URL: https://github.com/johnstonskj/idea-settings.git
# cask 'intellij-idea-ce'

# cask 'sublime-text'
# cask 'sublime-merge'

# mas 'Tap Forms Organizer 5 Database', id: 1081981112
# mas 'Tap Forms Database Pro', id: 1527890083

# ---------------------------------------------------------------------------------------------------------------------
# Layer 04 => Development Tools ❱ Programming Languages
# ---------------------------------------------------------------------------------------------------------------------

# GCC GNU Compiler Collection
brew 'gcc'

# LLVM compiler
brew 'llvm'

# GNU CLISP, a Common Lisp implementation
brew 'clisp'

# Coq proof assistant for higher-order logic
brew 'rocq'
brew 'rocq-elpi'

# GNU Ubiquitous Intelligent Language for Extensions
brew 'guile'
brew 'guile-fibers'
brew 'guile-gnutls'

# Node.js is a JavaScript platform for building fast, scalable network app.
brew 'node'
brew 'nvm'

# V8 JavaScript Engine.
brew 'v8'

# OCaml: General purpose programming language in the ML family
brew 'ocaml'
brew 'ocaml-findlib'
brew 'ocaml-zarith'
brew 'ocamlbuild'
brew 'opam'

# Python programming language, esp. for systems scripting.
brew 'python3'
brew 'uv'

# Ruby programming language; compare `perl`, `python`.
brew 'ruby'

# Rust!!!!
brew 'rustup'

# LSP server for Rust
brew 'rust-analyzer'

# Cargo commands
brew 'cargo-audit'
brew 'cargo-binstall'
brew 'cargo-depgraph'
brew 'cargo-edit'
brew 'cargo-flamegraph'
brew 'cargo-expand'
brew 'cargo-generate'
brew 'cargo-nextest'
brew 'cargo-shear'
brew 'cargo-update'
brew 'cargo-watch'

# Modern programming language in the Lisp/Scheme family
cask 'racket'

# A variety of scheme implementations
brew 'chezscheme'
# brew 'chibi-scheme'
# brew 'gambit-scheme'
# brew 'gerbil-scheme'
# brew 'mit-scheme'
# brew 'sagittarius-scheme'
# brew 'scheme48'
# brew 'sisc-scheme'

# High-performance system programming language.
brew 'swift'
brew 'swiftly'
brew 'swift-format'
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

# Carthage Xcode project dependency manager.
brew 'carthage'

# Terminal-based AI coding assistant
cask 'claude-code'
brew 'claude-cmd'
brew 'claude-hooks'
brew 'claudekit'

# Finder extension to use Git
mas 'SnailGit – Git for Finder', id: 847260112

cask 'jupyter-notebook-ql'
cask 'jupyter-notebook-viewer'
cask 'jupyterlab-app'

# Swift Development Tools from the Mac App Store
mas 'Swift Playground', id: 1496833156
mas 'Swifter for SwiftUI', id: 1621133381
mas 'DetailsPro', id: 1524366536

# Make iOS and macOS widgets in JavaScript
mas 'ScriptWidget', id: 1555600758

mas 'SQLPro Studio', id: 985614903

mas 'Ninox Database', id: 901110441

# ---------------------------------------------------------------------------------------------------------------------
# Layer 04 => Development Tools ❱ Runtime
# ---------------------------------------------------------------------------------------------------------------------

brew 'awscli'
brew 'awscli-local'
brew 'aws-cdk'
brew 'aws-keychain'

# SQLite database: self-contained, serverless, zero-configuration, transactional engine.
brew 'sqlite', link: true

# High-performance, asynchronous messaging library
brew 'zeromq'

## ====================================================================================================================
## Layer 05 => Personal Apps
## ====================================================================================================================

# Track money & budgets
mas 'Copilot: Track & Budget Money', id: 1447330651

# Music Creation and MIDI Tools
cask 'midikeys'
cask 'bitwig-studio'
cask 'native-access'

mas 'GarageBand', id: 682658836

mas 'Audulus 4', id: 1592022030
mas 'Animoog Z Synthesizer', id: 1586841361
mas 'Minimoog Model D Synthesizer', id: 1339418001
mas 'Model 15 Modular Synthesizer', id: 1041465860

mas 'MIDI Connect', id: 6476070288
mas 'QuickMIDI', id: 1459790045
mas 'Widi Plus', id: 1115231926

# MUsic Listening
mas 'Endel: Focus & Sleep Sounds', id: 1346247457
mas 'Silicio Mini Player + Widgets', id: 933627574

# mas 'Linn', id: 1292218680 <= iPad app
mas 'Linn Kazoo', id: 848937349

# The best dive logger
mas 'DiveLogDT', id: 411603212

# Widgets
mas 'Lockera Widgets', id: 6466819847
mas 'iStatistica Pro', id: 1447778660

# Finder/Menubar extensions
mas 'New Terminal Here', id: 1067646949
mas 'Webcam Settings', id: 533696630
# mas 'QR Clipboard', id: 869183896 <= maybe?

# Amateur Radio
mas 'Morse: Code training to CW guru', id: 923315129
mas 'QTH.app', id: 6740310746
mas 'SDR Control for Icom', id: 1592313285
mas 'RUMlogNG', id: 964454561

# General Odds and Ends
# mas 'Parcel - Delivery Tracking', id: 375589283
