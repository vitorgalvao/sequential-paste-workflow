# <img src='Workflow/icon.png' width='45' align='center' alt='icon'> Sequential Paste Alfred Workflow

Paste previous clipboard entries in order

[⤓ Install on the Alfred Gallery](https://alfred.app/workflows/vitor/sequential-paste)

## Usage

Paste clipboard entries sequentially via the [Hotkey](https://www.alfredapp.com/help/workflows/triggers/hotkey/) or [Snippet Trigger](https://www.alfredapp.com/help/workflows/triggers/snippet/). Each call pastes the preceding clipboard entry.

Copying from the most recent item restarts if the last paste is older than the timeout minutes defined in the [Workflow’s Configuration](https://www.alfredapp.com/help/workflows/user-configuration/). A force reset can be triggered with the `paste` keyword by pressing <kbd>⌘</kbd><kbd>⌥</kbd><kbd>⌃</kbd><kbd>↩&#xFE0E;</kbd>.

![Paste Keyword](Workflow/images/about/paste.png)
