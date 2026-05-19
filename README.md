```json
// Zed settings
//
// For information on how to configure Zed, see the Zed
// documentation: https://zed.dev/docs/configuring-zed
//
// To see all of Zed's default settings without changing your
// custom settings, run `zed: open default settings` from the
// command palette (cmd-shift-p / ctrl-shift-p)
{
  // AI
  "cli_default_open_behavior": "existing_window",
  "outline_panel": {
    "dock": "left",
  },
  "collaboration_panel": {
    "dock": "left",
  },
  "git_panel": {
    "dock": "left",
  },
  "lsp": {
    "vtsls": {
      "settings": {
        "typescript": {
          "updateImportsOnFileMove": {
            "enabled": "never",
          },
        },
        "javascript": {
          "updateImportsOnFileMove": {
            "enabled": "never",
          },
        },
      },
      "enable_lsp_tasks": true,
    },
  },
  "agent": {
    "dock": "right",
    "default_model": {
      "provider": "copilot_chat",
      "model": "gpt-4o",
    },
  },

  // UI
  "ui_font_size": 15,
  "buffer_font_size": 14,
  "buffer_font_family": "Monocraft",
  "ui_font_family": "Monocraft",
  "title_bar": {
    "show_onboarding_banner": false,
    "show_project_items": false,
    "show_branch_name": true,
    "show_user_menu": false,
    "show_sign_in": false,
  },
  "tab_bar": {
    "show": true,
  },
  "toolbar": {
    "quick_actions": false,
  },
  "status_bar": {
    "experimental.show": false,
  },
  "project_panel": {
    "dock": "right",
    "default_width": 400,
    "hide_root": true,
    "auto_fold_dirs": true,
    "starts_open": false,
    "scrollbar": {
      "show": "never",
    },
  },

  // Theming
  "icon_theme": {
    "mode": "light",
    "light": "Zed (Default)",
    "dark": "Zed (Default)",
  },
  "theme": {
    "mode": "dark",
    "light": "Everforest Light Hard (material)",
    "dark": "Vesper",
  },
}
```
