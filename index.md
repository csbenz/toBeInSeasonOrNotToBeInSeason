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

Surveys show that most people don't know anything about food seasons [0]. With the globalisation of our society, food is transported around the world and most fruits and vegetables can be found all year round on the supermarket's shelves. Vegetables and fruits used to grow in your garden or were bought from the local farmer, and this locality forced eating seasonal food.

The transportation of food is a large factor of pollution, with trucks and cargos moving the food around the globe, sometimes several times.

In this story we analyze when and how food is consumed in America, and if the food is consumed according to its season.

We base our data on user rating dates from large cooking recipe websites which were scrapped by Stanford's infolab.
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
        "6549c5d796f843b3bb1445065932f2c3": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "25347b49c3a344b8bff1c0c10537954e": {
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
                    "IPY_MODEL_61b6953cd09c4044a927e2d080ab636a",
                    "IPY_MODEL_4036e0f0cd634979a8bf0ef92571d83d"
                ],
                "layout": "IPY_MODEL_6549c5d796f843b3bb1445065932f2c3"
            }
        },
        "514418f658934fde9ad210b0d4779763": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "66150f562839423bb2c72f01403ada2d": {
            "model_name": "SliderStyleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "61b6953cd09c4044a927e2d080ab636a": {
            "model_name": "IntSliderModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "x",
                "layout": "IPY_MODEL_514418f658934fde9ad210b0d4779763",
                "max": 27,
                "min": -9,
                "style": "IPY_MODEL_66150f562839423bb2c72f01403ada2d",
                "value": 24
            }
        },
        "68e34158a67e4b2b85252f39d7ed6562": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "4036e0f0cd634979a8bf0ef92571d83d": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_68e34158a67e4b2b85252f39d7ed6562",
                "msg_throttle": 1
            }
        },
        "ded39e9b125442aaaa4cf97a06d57866": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "05789e9ca4de4d2fb885373e7c5e4f57": {
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
                "layout": "IPY_MODEL_ded39e9b125442aaaa4cf97a06d57866",
                "value": "january"
            }
        },
        "869bb93145cd413597d1d81f903fbf41": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "785a31bd47de4c029b15bf0db5cf4fe8": {
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
                    "IPY_MODEL_05789e9ca4de4d2fb885373e7c5e4f57",
                    "IPY_MODEL_bbeac041fe4d4987827a6cd0b6382292"
                ],
                "layout": "IPY_MODEL_869bb93145cd413597d1d81f903fbf41"
            }
        },
        "3e65bf111419438d8ff2db53226ffc83": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "bbeac041fe4d4987827a6cd0b6382292": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_3e65bf111419438d8ff2db53226ffc83",
                "msg_throttle": 1
            }
        },
        "be5004e3e74447e7982924b67dae57e8": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "a470af1e09144302b24c5815ebc68822": {
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
                "layout": "IPY_MODEL_be5004e3e74447e7982924b67dae57e8",
                "value": "january"
            }
        },
        "49f56046a2ab46ac84d8ba7da832bd96": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "eff5fd3dadb747a09cf4ab753961daf1": {
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
                    "IPY_MODEL_a470af1e09144302b24c5815ebc68822",
                    "IPY_MODEL_e6eaeb0adb67423aadf82ef7bab9a18b"
                ],
                "layout": "IPY_MODEL_49f56046a2ab46ac84d8ba7da832bd96"
            }
        },
        "449c10ef21694b5aa4d116dd316a739c": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "e6eaeb0adb67423aadf82ef7bab9a18b": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_449c10ef21694b5aa4d116dd316a739c",
                "msg_throttle": 1
            }
        }
    }
}
</script>
<script type="application/vnd.jupyter.widget-view+json">
{
    "model_id": "eff5fd3dadb747a09cf4ab753961daf1"
}
</script>
<script type="application/vnd.jupyter.widget-view+json">
{
    "model_id": "a470af1e09144302b24c5815ebc68822"
}
</script>









<h1>Conclusion</h1>

<h1>Citations</h1>

@inproceedings{WestWhiteHorvitzWWW2013,
  title={		From Cookies to Cooks: Insights on Dietary Patterns via Analysis of Web Usage Logs},
  author={		Robert West and Ryen W. White and Eric Horvitz},
  booktitle={	Proceedings of the 22nd International World Wide Web Conference},
  year={		2013}
}

<iframe src="map_test.html" width="100%" height="400"></iframe>

