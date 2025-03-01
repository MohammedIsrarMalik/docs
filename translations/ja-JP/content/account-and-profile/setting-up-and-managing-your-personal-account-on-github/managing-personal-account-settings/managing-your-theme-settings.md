---
title: テーマ設定を管理する
intro: 'You can manage how {% data variables.product.product_name %} looks to you by setting a theme preference that either follows your system settings or always uses a light or dark mode.'
versions:
  fpt: '*'
  ghae: '*'
  ghes: '*'
  ghec: '*'
topics:
  - Accounts
redirect_from:
  - /github/setting-up-and-managing-your-github-user-account/managing-your-theme-settings
  - /github/setting-up-and-managing-your-github-user-account/managing-user-account-settings/managing-your-theme-settings
  - /account-and-profile/setting-up-and-managing-your-github-user-account/managing-user-account-settings/managing-your-theme-settings
shortTitle: Manage theme settings
---

{% data variables.product.product_name %} を使用時期と使用方法を選択して柔軟性を高めるために、テーマ設定をして {% data variables.product.product_name %} の外観を変更できます。 You can choose from themes that are light or dark, or you can configure {% data variables.product.product_name %} to follow your system settings.

You may want to use a dark theme to reduce power consumption on certain devices, to reduce eye strain in low-light conditions, or because you prefer how the theme looks.

{% ifversion fpt or ghes > 3.2 or ghae or ghec %}If you have low vision, you may benefit from a high contrast theme, with greater contrast between foreground and background elements.{% endif %}{% ifversion fpt or ghae or ghec %} If you have colorblindness, you may benefit from our light and dark colorblind themes.

{% endif %}

{% data reusables.user-settings.access_settings %}
{% data reusables.user-settings.appearance-settings %}

1. Under "Theme mode", select the drop-down menu, then click a theme preference.

   ![Drop-down menu under "Theme mode" for selection of theme preference](/assets/images/help/settings/theme-mode-drop-down-menu.png)
1. 使いたいテーマをクリックしてください。
    - If you chose a single theme, click a theme.

      {% ifversion fpt or ghes > 3.2 or ghae or ghec %}![Radio buttons for the choice of a single theme](/assets/images/help/settings/theme-choose-a-single-theme-highcontrast.png){% else %}![Radio buttons for the choice of a single theme](/assets/images/help/settings/theme-choose-a-single-theme.png){% endif %}
    - If you chose to follow your system settings, click a day theme and a night theme.

      {% ifversion fpt or ghes > 3.2 or ghae or ghec %}![Buttons for the choice of a theme to sync with the system setting](/assets/images/help/settings/theme-choose-a-day-and-night-theme-to-sync-highcontrast.png){% else %}![Buttons for the choice of a theme to sync with the system setting](/assets/images/help/settings/theme-choose-a-day-and-night-theme-to-sync.png){% endif %}
    {% ifversion fpt or ghec %}
    - If you would like to choose a theme which is currently in public beta, you will first need to enable it with feature preview. For more information, see "[Exploring early access releases with feature preview](/get-started/using-github/exploring-early-access-releases-with-feature-preview)."{% endif %}

{% ifversion command-palette %}

{% note %}

**Note:** You can also change your theme settings with the command palette. For more information, see "[{% data variables.product.prodname_command_palette %}](/get-started/using-github/github-command-palette)".

{% endnote %}

{% endif %}

## 参考リンク

- "[{% data variables.product.prodname_desktop %}用のテーマの設定方法](/desktop/installing-and-configuring-github-desktop/setting-a-theme-for-github-desktop)"
