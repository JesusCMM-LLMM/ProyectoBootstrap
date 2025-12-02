# ~/.config/starship.toml

add_newline = true

[character]
success_symbol = "[➜](bold green)"
error_symbol = "[✗](bold red)"

[directory]
style = "bold cyan"
truncation_length = 3
truncate_to_repo = false

[git_branch]
style = "bold purple"
symbol = " "

[git_status]
style = "bold red"
format = '([$all_status$ahead_behind]($style) )'

[nodejs]
symbol = " "
style = "bold green"

[python]
symbol = "🐍 "
style = "bold yellow"

[docker_context]
symbol = " "
style = "bold blue"

[package]
disabled = true
