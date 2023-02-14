# Markdown hidden blocks

## Using attribute Lists

This is a hidden paragraph.
{: .hidden }

### Hidden heading {: .hidden }

![Hidden image](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg){: .hidden }

[link](#top){: .hidden }

``` { .python .hidden }
print('Hello')
```

!!! note hidden "Title"
    Hidden admonition

??? note hidden "Open styled details"

    ??? danger "Nested details!"
        And more content again.

!!! type hidden "Title"
    Any hidden content

??? note "Решение"
    [![](https://mermaid.ink/img/pako:eNpNUM1Kw0AQfpVhLjbQWtpjQE_1CfSWzWFpNnYh2ZRkg0gaqAr1IvTmwYuvILVRibTPMPtGTqRU2b9h5vu--XYqnGaRQh_jJLuZzmRu4WoiDEDRC-iV9u6R3tw97akNPRgMzkFno2AoUMIZBNrYXuFBnOVQgDa856XteafFPNH8hgKHYafFnF8uA0dVJZC29O3WQC3rftCO73fag0pUqowF-gQZ-P6Y6XXd0Tvaofe4600b-uLTuDt29nXkCcay3cYtqWGNE160ARbfMnwHbunWHPJPOltHP_8acGZBrXtmR41buSdwK2a27PVhAYrn8fJXCz1hsI-pylOpI55f1QkJtDM2I9DnMFKxLBMrUJiaobK02eWtmaJv81L1sZxH0qqJlte5TNGPZVIcsxeRtll-SNY_KLCy-Q?type=png)](https://mermaid.live/edit#pako:eNpNUM1Kw0AQfpVhLjbQWtpjQE_1CfSWzWFpNnYh2ZRkg0gaqAr1IvTmwYuvILVRibTPMPtGTqRU2b9h5vu--XYqnGaRQh_jJLuZzmRu4WoiDEDRC-iV9u6R3tw97akNPRgMzkFno2AoUMIZBNrYXuFBnOVQgDa856XteafFPNH8hgKHYafFnF8uA0dVJZC29O3WQC3rftCO73fag0pUqowF-gQZ-P6Y6XXd0Tvaofe4600b-uLTuDt29nXkCcay3cYtqWGNE160ARbfMnwHbunWHPJPOltHP_8acGZBrXtmR41buSdwK2a27PVhAYrn8fJXCz1hsI-pylOpI55f1QkJtDM2I9DnMFKxLBMrUJiaobK02eWtmaJv81L1sZxH0qqJlte5TNGPZVIcsxeRtll-SNY_KLCy-Q){: .hidden1 }
    
    ![](https://i.imgur.com/TgmTfLL.png){: .hidden }
    
    ``` {.hidden}
    вводим список a с помощью генератора [int(s) for s in input().split()]
    для каждого element в срезе списке a[::2]:
        вывести element через ' ' в одну строку
    ```