## To be in season or not to be in season: a food consumption analysis

<p>
  <strong>By Kate Dopiro, Fabien Zellweger & Christopher Benz</strong>
</p>

<p>
  <em>Data story for the end-of-semester project of the ADA course at EPFL.</em>
</p>

<p>
  This page is best viewed in the Chromium browser. Other browsers such as Firefox may not display some mvisualizations correctly.
</p>


<h1>Introduction</h1>

<h1>Data</h1>


<h1>Results</h1>

<!--<link rel="import" href="us_map.html">-->
<!--<iframe src="us_map.html" width="100%" height="400">hmm kay</iframe>-->

<script src="https://unpkg.com/jupyter-js-widgets@~2.1.4/dist/embed.js"></script>
<script type="application/vnd.jupyter.widget-state+json">
{
    "version_major": 1,
    "version_minor": 0,
    "state": {
        "d2bc508e105b4c378f0ea44888646136": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "4943f7b258b74d8781fe6b6f13ef718b": {
            "model_name": "DropdownModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "january",
                    "february",
                    "march",
                    "april",
                    "may",
                    "june",
                    "july",
                    "august",
                    "september",
                    "october",
                    "november",
                    "december"
                ],
                "_view_module_version": "~2.1.4",
                "description": "Month:",
                "layout": "IPY_MODEL_d2bc508e105b4c378f0ea44888646136",
                "value": "january"
            }
        },
        "47676be57561464297125f6f7a0b08e6": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "b1c167eefeca48c387d9616fadd041a4": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_4943f7b258b74d8781fe6b6f13ef718b",
                    "IPY_MODEL_22ddf2c3728e473196f206f30454edd1"
                ],
                "layout": "IPY_MODEL_47676be57561464297125f6f7a0b08e6"
            }
        },
        "905295b2a27641068339ec53b084ca62": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "22ddf2c3728e473196f206f30454edd1": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_905295b2a27641068339ec53b084ca62",
                "msg_throttle": 1
            }
        },
        "203b3088c19940ef9ffada16737c98f8": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "6e416ebe597047cbab460308ce02ce2a": {
            "model_name": "DropdownModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "january",
                    "february",
                    "march",
                    "april",
                    "may",
                    "june",
                    "july",
                    "august",
                    "september",
                    "october",
                    "november",
                    "december"
                ],
                "_view_module_version": "~2.1.4",
                "description": "Month:",
                "layout": "IPY_MODEL_203b3088c19940ef9ffada16737c98f8",
                "value": "january"
            }
        },
        "f026ab3d973942398e6e58fdf9d4bb47": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "382ec23d72d546f8a996dab1a4d94c1c": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_6e416ebe597047cbab460308ce02ce2a",
                    "IPY_MODEL_ef117749a4de4ef5af687d8859217243"
                ],
                "layout": "IPY_MODEL_f026ab3d973942398e6e58fdf9d4bb47"
            }
        },
        "5eeb0ab0178544ea9aa3f4b5f0a2affc": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "ef117749a4de4ef5af687d8859217243": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_5eeb0ab0178544ea9aa3f4b5f0a2affc",
                "msg_throttle": 1
            }
        },
        "51aa8c8ea61041be9763606cdbf4f383": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "090834d44c39484ebf11f8fbf2b67438": {
            "model_name": "DropdownModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "january",
                    "february",
                    "march",
                    "april",
                    "may",
                    "june",
                    "july",
                    "august",
                    "september",
                    "october",
                    "november",
                    "december"
                ],
                "_view_module_version": "~2.1.4",
                "description": "Month:",
                "layout": "IPY_MODEL_51aa8c8ea61041be9763606cdbf4f383",
                "value": "january"
            }
        },
        "c0e4a5c6caaa4510929173e2544bab32": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "a37bd5ccfe694a7294ccaad79109bacb": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_090834d44c39484ebf11f8fbf2b67438",
                    "IPY_MODEL_c28510718e904679a9c8d134094f92e4"
                ],
                "layout": "IPY_MODEL_c0e4a5c6caaa4510929173e2544bab32"
            }
        },
        "b0a901faf7f346f99ef24d4bcfb66e65": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "c28510718e904679a9c8d134094f92e4": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_b0a901faf7f346f99ef24d4bcfb66e65",
                "msg_throttle": 1
            }
        },
        "1920955fd0ef4bed91fa9b733a49c2ad": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "227dd850fdfe46e9954e204a1f14016d": {
            "model_name": "DropdownModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "january",
                    "february",
                    "march",
                    "april",
                    "may",
                    "june",
                    "july",
                    "august",
                    "september",
                    "october",
                    "november",
                    "december"
                ],
                "_view_module_version": "~2.1.4",
                "description": "Month:",
                "layout": "IPY_MODEL_1920955fd0ef4bed91fa9b733a49c2ad",
                "value": "january"
            }
        },
        "eb1d1628dda3469eb540f31218441b7d": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "a291e720664e47b9bb37319d1ac9a4b2": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_227dd850fdfe46e9954e204a1f14016d",
                    "IPY_MODEL_62b9c98d844d43d39fa6f17b38cf9e60"
                ],
                "layout": "IPY_MODEL_eb1d1628dda3469eb540f31218441b7d"
            }
        },
        "39f3e147170b494fbc4052b1981b1dfd": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "62b9c98d844d43d39fa6f17b38cf9e60": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_39f3e147170b494fbc4052b1981b1dfd",
                "msg_throttle": 1
            }
        },
        "61cbf85e9ba34f51a5521a5021ef5bd2": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "ebae758e5ca847fa8d2e5a6ac0cc1b40": {
            "model_name": "DropdownModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "january",
                    "february",
                    "march",
                    "april",
                    "may",
                    "june",
                    "july",
                    "august",
                    "september",
                    "october",
                    "november",
                    "december"
                ],
                "_view_module_version": "~2.1.4",
                "description": "Month:",
                "layout": "IPY_MODEL_61cbf85e9ba34f51a5521a5021ef5bd2",
                "value": "january"
            }
        },
        "abf10712d99b40449737ecfbe37a29b4": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "b6840ea184db4430a650c04187692abd": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_ebae758e5ca847fa8d2e5a6ac0cc1b40",
                    "IPY_MODEL_e065d3fb8dd94cf2bc112fa8f1636b1e"
                ],
                "layout": "IPY_MODEL_abf10712d99b40449737ecfbe37a29b4"
            }
        },
        "c402381c969c4cc0ad71f4c199b26b40": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "e065d3fb8dd94cf2bc112fa8f1636b1e": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_c402381c969c4cc0ad71f4c199b26b40",
                "msg_throttle": 1
            }
        }
    }
}
</script>
<script type="application/vnd.jupyter.widget-view+json">
{
    "model_id": "b6840ea184db4430a650c04187692abd"
}
</script>





<h1>Conclusion</h1>

<iframe src="map_test.html" width="100%" height="400"></iframe>

