# AsciiUI
A retro UI to power Ts3

- go from Text to Interactive UI
- priorities:
    - clarity of actions
    - speed of interactions

From This: 
<pre id="ascii-renderer" class="ascii-ui" style="margin:0; border-radius: 4px;">
+---------------------------------------------------------------------+
|                           .Target Scope.                        [☀︎] |--line_style: { color: #4E75D0 }
|                                                                     |
| ( ) Apply to All Windows      ( ) Apply to Current Window           |
| ( ) Apply to Current Domain   ( ) Apply to Selected Tabs Only       |
+---------------------------------------------------------------------+
|                             .Actions.                               |--line_style: { color: #4E75D0 }
|                                                                     |
|     To organize        To Manage sessions         To Cleanup        |--line_style: { color: #4E75D0 }
|           ↓                     ↓                      ↓            |--line_style: { color: #4E75D0 }
|   [ Merge         ]    [ Save           ]    [ Clean Up Memory  ]   |
|   [ Sort          ]    [ Load           ]    [ Remove Duplicates]   |
|   [ Stack         ]    [ Focus          ]    [ Close            ]   |
|   [ Split         ]    [ Unfocus        ]    [ Tidy Up          ]   |
|   [ Shuffle       ]    [ Refresh        ]                           |
|                        [ Copy           ]                           |
+---------------------------------------------------------------------+
|                       Feedback and Settings                         |--line_style: { color: #4E75D0 }
+---------------------------------------------------------------------+
| [ *Feedback* ]                                          version %%% |--line_style: { color: #4E75D0 } --linked_data: ["version"]
| [ Reset ]                      %%% tabs opened accross %%%% windows |--line_style: { color: #4E75D0 } --linked_data: ["total_tabs", "total_windows"]
| [ Donate ]                                             %%%% domains |--line_style: { color: #4E75D0 } --linked_data: ["total_domains"]
|                                                 %%%% duplicate tabs |--line_style: { color: #4E75D0 } --linked_data: ["duplicate_tabs"]
|                                                                     |--line_style: { color: #4E75D0 } --linked_data: ["duplicate_tabs"]
+---------------------------------------------------------------------+
|                               .Ts3.                                 |
+---------------------------------------------------------------------+</pre>

To: 

<img width="579" alt="image" src="https://github.com/user-attachments/assets/a088d504-af23-45ce-96a2-6ef6d244cb1c" />

