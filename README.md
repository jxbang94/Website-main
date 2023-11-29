Link to Hannah and Jason's Project website: https://jxbang94.github.io/Website-main/

{
  "requestedUrl": "https://jxbang94.github.io/Website-main/",
  "finalUrl": "https://jxbang94.github.io/Website-main/",
  "mainDocumentUrl": "https://jxbang94.github.io/Website-main/",
  "finalDisplayedUrl": "https://jxbang94.github.io/Website-main/",
  "lighthouseVersion": "11.0.0",
  "userAgent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) HeadlessChrome/119.0.6045.123 Safari/537.36",
  "fetchTime": "2023-11-29T08:13:49.811Z",
  "environment": {
    "networkUserAgent": "Mozilla/5.0 (Linux; Android 11; moto g power (2022)) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/109.0.0.0 Mobile Safari/537.36",
    "hostUserAgent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) HeadlessChrome/119.0.6045.123 Safari/537.36",
    "benchmarkIndex": 448.5,
    "credits": {
      "axe-core": "4.7.2"
    }
  },
  "runWarnings": [],
  "configSettings": {
    "emulatedFormFactor": "mobile",
    "formFactor": "mobile",
    "locale": "en-US",
    "onlyCategories": [
      "pwa",
      "performance",
      "accessibility",
      "best-practices",
      "seo"
    ],
    "channel": "lr"
  },
  "audits": {
    "third-party-summary": {
      "id": "third-party-summary",
      "title": "Minimize third-party usage",
      "description": "Third-party code can significantly impact load performance. Limit the number of redundant third-party providers and try to load third-party code after your page has primarily finished loading. [Learn how to minimize third-party impact](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/loading-third-party-javascript/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "displayValue": "Third-party code blocked the main thread for 0 ms",
      "details": {
        "headings": [
          {
            "label": "Third-Party",
            "key": "entity",
            "valueType": "text",
            "subItemsHeading": {
              "key": "url",
              "valueType": "url"
            }
          },
          {
            "valueType": "bytes",
            "subItemsHeading": {
              "key": "transferSize"
            },
            "label": "Transfer Size",
            "key": "transferSize",
            "granularity": 1
          },
          {
            "granularity": 1,
            "key": "blockingTime",
            "valueType": "ms",
            "label": "Main-Thread Blocking Time",
            "subItemsHeading": {
              "key": "blockingTime"
            }
          }
        ],
        "isEntityGrouped": true,
        "type": "table",
        "summary": {
          "wastedBytes": 83773,
          "wastedMs": 0
        },
        "items": [
          {
            "subItems": {
              "type": "subitems",
              "items": [
                {
                  "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css",
                  "mainThreadTime": 17.868000000000002,
                  "transferSize": 21238,
                  "blockingTime": 0
                },
                {
                  "transferSize": 18925,
                  "mainThreadTime": 0,
                  "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/fonts/glyphicons-halflings-regular.woff2",
                  "blockingTime": 0
                },
                {
                  "transferSize": 12185,
                  "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js",
                  "mainThreadTime": 13.692,
                  "blockingTime": 0
                }
              ]
            },
            "entity": "Bootstrap CDN",
            "mainThreadTime": 31.560000000000002,
            "transferSize": 52348,
            "blockingTime": 0
          },
          {
            "subItems": {
              "type": "subitems",
              "items": [
                {
                  "url": "https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js",
                  "blockingTime": 0,
                  "transferSize": 31425,
                  "mainThreadTime": 77.596
                }
              ]
            },
            "blockingTime": 0,
            "entity": "Google CDN",
            "transferSize": 31425,
            "mainThreadTime": 77.596
          }
        ]
      }
    },
    "main-thread-tasks": {
      "id": "main-thread-tasks",
      "title": "Tasks",
      "description": "Lists the toplevel main thread tasks that executed during page load.",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "headings": [
          {
            "key": "startTime",
            "granularity": 1,
            "valueType": "ms",
            "label": "Start Time"
          },
          {
            "label": "End Time",
            "valueType": "ms",
            "granularity": 1,
            "key": "duration"
          }
        ],
        "type": "table",
        "items": [
          {
            "duration": 12.298,
            "startTime": 72.043
          },
          {
            "startTime": 109.233,
            "duration": 12.378
          },
          {
            "startTime": 126.478,
            "duration": 17.696
          },
          {
            "startTime": 244.14,
            "duration": 5.341
          }
        ]
      }
    },
    "duplicate-id-active": {
      "id": "duplicate-id-active",
      "title": "`[id]` attributes on active, focusable elements are unique",
      "description": "All focusable elements must have a unique `id` to ensure that they're visible to assistive technologies. [Learn how to fix duplicate `id`s](https://dequeuniversity.com/rules/axe/4.7/duplicate-id-active).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "is-crawlable": {
      "id": "is-crawlable",
      "title": "Page isn’t blocked from indexing",
      "description": "Search engines are unable to include your pages in search results if they don't have permission to crawl them. [Learn more about crawler directives](https://developer.chrome.com/docs/lighthouse/seo/is-crawlable/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "headings": [],
        "type": "table"
      },
      "warnings": []
    },
    "crawlable-anchors": {
      "id": "crawlable-anchors",
      "title": "Links are crawlable",
      "description": "Search engines may use `href` attributes on links to crawl websites. Ensure that the `href` attribute of anchor elements links to an appropriate destination, so more pages of the site can be discovered. [Learn how to make links crawlable](https://support.google.com/webmasters/answer/9112205)",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "first-meaningful-paint": {
      "id": "first-meaningful-paint",
      "title": "First Meaningful Paint",
      "description": "First Meaningful Paint measures when the primary content of a page is visible. [Learn more about the First Meaningful Paint metric](https://developer.chrome.com/docs/lighthouse/performance/first-meaningful-paint/).",
      "score": 0.95,
      "scoreDisplayMode": "numeric",
      "displayValue": "2.0 s",
      "numericValue": 1985.5,
      "numericUnit": "millisecond"
    },
    "critical-request-chains": {
      "id": "critical-request-chains",
      "title": "Avoid chaining critical requests",
      "description": "The Critical Request Chains below show you what resources are loaded with a high priority. Consider reducing the length of chains, reducing the download size of resources, or deferring the download of unnecessary resources to improve page load. [Learn how to avoid chaining critical requests](https://developer.chrome.com/docs/lighthouse/performance/critical-request-chains/).",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "3 chains found",
      "details": {
        "chains": {
          "F4301FD72511EF55EBEFC04B58A8F2D0": {
            "request": {
              "endTime": 3872842.779099,
              "transferSize": 3772,
              "url": "https://jxbang94.github.io/Website-main/",
              "startTime": 3872842.710425,
              "responseReceivedTime": 3872842.7790930006
            },
            "children": {
              "41.4": {
                "request": {
                  "transferSize": 12185,
                  "endTime": 3872842.805673,
                  "responseReceivedTime": 3872842.8056670004,
                  "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js",
                  "startTime": 3872842.792747
                }
              },
              "41.3": {
                "request": {
                  "transferSize": 31425,
                  "responseReceivedTime": 3872842.800009,
                  "startTime": 3872842.792483,
                  "endTime": 3872842.800015,
                  "url": "https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"
                }
              },
              "41.2": {
                "children": {
                  "41.16": {
                    "request": {
                      "responseReceivedTime": 3872842.909053,
                      "startTime": 3872842.840562,
                      "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/fonts/glyphicons-halflings-regular.woff2",
                      "transferSize": 18925,
                      "endTime": 3872842.909057
                    }
                  }
                },
                "request": {
                  "responseReceivedTime": 3872842.813795,
                  "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css",
                  "startTime": 3872842.792266,
                  "transferSize": 21238,
                  "endTime": 3872842.813801
                }
              }
            }
          }
        },
        "type": "criticalrequestchain",
        "longestChain": {
          "duration": 198.63199996948242,
          "length": 3,
          "transferSize": 18925
        }
      }
    },
    "no-unload-listeners": {
      "id": "no-unload-listeners",
      "title": "Avoids `unload` event listeners",
      "description": "The `unload` event does not fire reliably and listening for it can prevent browser optimizations like the Back-Forward Cache. Use `pagehide` or `visibilitychange` events instead. [Learn more about unload event listeners](https://web.dev/bfcache/#never-use-the-unload-event)",
      "score": 1,
      "scoreDisplayMode": "binary"
    },
    "aria-meter-name": {
      "id": "aria-meter-name",
      "title": "ARIA `meter` elements have accessible names",
      "description": "When a meter element doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn how to name `meter` elements](https://dequeuniversity.com/rules/axe/4.7/aria-meter-name).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "aria-text": {
      "id": "aria-text",
      "title": "Elements with the `role=text` attribute do not have focusable descendents.",
      "description": "Adding `role=text` around a text node split by markup enables VoiceOver to treat it as one phrase, but the element's focusable descendents will not be announced. [Learn more about the `role=text` attribute](https://dequeuniversity.com/rules/axe/4.7/aria-text).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "color-contrast": {
      "id": "color-contrast",
      "title": "Background and foreground colors do not have a sufficient contrast ratio.",
      "description": "Low-contrast text is difficult or impossible for many users to read. [Learn how to provide sufficient color contrast](https://dequeuniversity.com/rules/axe/4.7/color-contrast).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "items": [
          {
            "subItems": {
              "items": [
                {
                  "relatedNode": {
                    "selector": "div.container > div.row > div.col-sm-4 > div.well",
                    "type": "node",
                    "nodeLabel": "Genshin Impact",
                    "path": "1,HTML,1,BODY,3,MAIN,0,DIV,0,DIV,6,DIV,0,DIV",
                    "snippet": "<div class=\"well\">",
                    "boundingRect": {
                      "right": 600,
                      "left": 380,
                      "height": 60,
                      "bottom": 1006,
                      "width": 220,
                      "top": 946
                    },
                    "lhId": "1-1-DIV"
                  }
                }
              ],
              "type": "subitems"
            },
            "node": {
              "explanation": "Fix any of the following:\n  Element has insufficient color contrast of 4.17 (foreground color: #337ab7, background color: #f5f5f5, font size: 10.5pt (14px), font weight: normal). Expected contrast ratio of 4.5:1",
              "snippet": "<a href=\"genshin.html\">",
              "path": "1,HTML,1,BODY,3,MAIN,0,DIV,0,DIV,6,DIV,0,DIV,0,A",
              "nodeLabel": "Genshin Impact",
              "type": "node",
              "boundingRect": {
                "left": 441,
                "top": 968,
                "width": 98,
                "bottom": 984,
                "height": 16,
                "right": 539
              },
              "selector": "div.row > div.col-sm-4 > div.well > a",
              "lhId": "1-0-A"
            }
          },
          {
            "subItems": {
              "type": "subitems",
              "items": [
                {
                  "relatedNode": {
                    "selector": "div.container > div.row > div.col-sm-4 > div.well",
                    "path": "1,HTML,1,BODY,3,MAIN,3,DIV,0,DIV,2,DIV,1,DIV",
                    "boundingRect": {
                      "right": 850,
                      "left": 630,
                      "bottom": 1243,
                      "top": 1163,
                      "width": 220,
                      "height": 80
                    },
                    "lhId": "1-3-DIV",
                    "nodeLabel": "Daughter Spends $20,000 of Father's Money on Game",
                    "snippet": "<div class=\"well\">",
                    "type": "node"
                  }
                }
              ]
            },
            "node": {
              "explanation": "Fix any of the following:\n  Element has insufficient color contrast of 4.17 (foreground color: #337ab7, background color: #f5f5f5, font size: 10.5pt (14px), font weight: normal). Expected contrast ratio of 4.5:1",
              "path": "1,HTML,1,BODY,3,MAIN,3,DIV,0,DIV,2,DIV,1,DIV,0,A",
              "snippet": "<a href=\"https://www.straitstimes.com/singapore/community/dad-saddled-with-20000-cr…\">",
              "boundingRect": {
                "top": 1185,
                "height": 36,
                "right": 830,
                "bottom": 1221,
                "width": 179,
                "left": 650
              },
              "lhId": "1-2-A",
              "type": "node",
              "nodeLabel": "Daughter Spends $20,000 of Father's Money on Game",
              "selector": "div.row > div.col-sm-4 > div.well > a"
            }
          },
          {
            "subItems": {
              "items": [
                {
                  "relatedNode": {
                    "snippet": "<div class=\"well\">",
                    "lhId": "1-5-DIV",
                    "path": "1,HTML,1,BODY,3,MAIN,3,DIV,0,DIV,2,DIV,2,DIV",
                    "type": "node",
                    "selector": "div.container > div.row > div.col-sm-4 > div.well",
                    "boundingRect": {
                      "width": 220,
                      "top": 1263,
                      "height": 100,
                      "bottom": 1363,
                      "left": 630,
                      "right": 850
                    },
                    "nodeLabel": "Daughter Spends Family's Life Savings of $64,000 on Mobile Game"
                  }
                }
              ],
              "type": "subitems"
            },
            "node": {
              "explanation": "Fix any of the following:\n  Element has insufficient color contrast of 4.17 (foreground color: #337ab7, background color: #f5f5f5, font size: 10.5pt (14px), font weight: normal). Expected contrast ratio of 4.5:1",
              "nodeLabel": "Daughter Spends Family's Life Savings of $64,000 on Mobile Game",
              "boundingRect": {
                "right": 823,
                "bottom": 1341,
                "top": 1285,
                "height": 56,
                "left": 657,
                "width": 166
              },
              "selector": "div.row > div.col-sm-4 > div.well > a",
              "lhId": "1-4-A",
              "type": "node",
              "path": "1,HTML,1,BODY,3,MAIN,3,DIV,0,DIV,2,DIV,2,DIV,0,A",
              "snippet": "<a href=\"https://www.insider.com/teenage-girl-moms-debit-card-64000-mobile-games-fa…\">"
            }
          },
          {
            "node": {
              "boundingRect": {
                "right": 826,
                "height": 16,
                "left": 654,
                "width": 172,
                "top": 1405,
                "bottom": 1421
              },
              "selector": "div.row > div.col-sm-4 > div.well > a",
              "type": "node",
              "nodeLabel": "The Cybersmile Foundation",
              "explanation": "Fix any of the following:\n  Element has insufficient color contrast of 4.17 (foreground color: #337ab7, background color: #f5f5f5, font size: 10.5pt (14px), font weight: normal). Expected contrast ratio of 4.5:1",
              "path": "1,HTML,1,BODY,3,MAIN,3,DIV,0,DIV,2,DIV,3,DIV,0,A",
              "lhId": "1-6-A",
              "snippet": "<a href=\"https://www.cybersmile.org/what-we-do/total-access-support\">"
            },
            "subItems": {
              "type": "subitems",
              "items": [
                {
                  "relatedNode": {
                    "nodeLabel": "The Cybersmile Foundation",
                    "boundingRect": {
                      "height": 60,
                      "width": 220,
                      "bottom": 1443,
                      "left": 630,
                      "right": 850,
                      "top": 1383
                    },
                    "lhId": "1-7-DIV",
                    "type": "node",
                    "selector": "div.container > div.row > div.col-sm-4 > div.well",
                    "snippet": "<div class=\"well\">",
                    "path": "1,HTML,1,BODY,3,MAIN,3,DIV,0,DIV,2,DIV,3,DIV"
                  }
                }
              ]
            }
          }
        ],
        "headings": [
          {
            "label": "Failing Elements",
            "valueType": "node",
            "key": "node",
            "subItemsHeading": {
              "valueType": "node",
              "key": "relatedNode"
            }
          }
        ],
        "debugData": {
          "type": "debugdata",
          "tags": [
            "cat.color",
            "wcag2aa",
            "wcag143",
            "ACT",
            "TTv5",
            "TT13.c"
          ],
          "impact": "serious"
        }
      }
    },
    "aria-hidden-body": {
      "id": "aria-hidden-body",
      "title": "`[aria-hidden=\"true\"]` is not present on the document `<body>`",
      "description": "Assistive technologies, like screen readers, work inconsistently when `aria-hidden=\"true\"` is set on the document `<body>`. [Learn how `aria-hidden` affects the document body](https://dequeuniversity.com/rules/axe/4.7/aria-hidden-body).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "type": "table",
        "headings": []
      }
    },
    "network-requests": {
      "id": "network-requests",
      "title": "Network Requests",
      "description": "Lists the network requests that were made during page load.",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "headings": [
          {
            "label": "URL",
            "key": "url",
            "valueType": "url"
          },
          {
            "valueType": "text",
            "label": "Protocol",
            "key": "protocol"
          },
          {
            "granularity": 1,
            "label": "Network Request Time",
            "valueType": "ms",
            "key": "networkRequestTime"
          },
          {
            "valueType": "ms",
            "key": "networkEndTime",
            "granularity": 1,
            "label": "Network End Time"
          },
          {
            "displayUnit": "kb",
            "label": "Transfer Size",
            "granularity": 1,
            "key": "transferSize",
            "valueType": "bytes"
          },
          {
            "label": "Resource Size",
            "displayUnit": "kb",
            "granularity": 1,
            "valueType": "bytes",
            "key": "resourceSize"
          },
          {
            "valueType": "text",
            "label": "Status Code",
            "key": "statusCode"
          },
          {
            "valueType": "text",
            "label": "MIME Type",
            "key": "mimeType"
          },
          {
            "label": "Resource Type",
            "key": "resourceType",
            "valueType": "text"
          }
        ],
        "debugData": {
          "networkStartTimeTs": 3872842709617,
          "type": "debugdata"
        },
        "type": "table",
        "items": [
          {
            "url": "https://jxbang94.github.io/Website-main/",
            "rendererStartTime": 0,
            "networkEndTime": 69.48199987411499,
            "mimeType": "text/html",
            "entity": "GitHub",
            "statusCode": 200,
            "priority": "VeryHigh",
            "sessionTargetType": "page",
            "finished": true,
            "resourceSize": 8670,
            "experimentalFromMainFrame": true,
            "transferSize": 3772,
            "resourceType": "Document",
            "networkRequestTime": 0.8080000877380371,
            "protocol": "h2"
          },
          {
            "mimeType": "text/css",
            "finished": true,
            "entity": "Bootstrap CDN",
            "resourceSize": 121457,
            "networkRequestTime": 82.64900016784668,
            "priority": "VeryHigh",
            "sessionTargetType": "page",
            "resourceType": "Stylesheet",
            "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css",
            "experimentalFromMainFrame": true,
            "statusCode": 200,
            "networkEndTime": 104.18400001525879,
            "transferSize": 21238,
            "rendererStartTime": 82.01599979400635,
            "protocol": "h2"
          },
          {
            "networkEndTime": 90.39800024032593,
            "protocol": "h2",
            "transferSize": 31425,
            "entity": "Google CDN",
            "resourceType": "Script",
            "priority": "High",
            "url": "https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js",
            "experimentalFromMainFrame": true,
            "resourceSize": 87533,
            "statusCode": 200,
            "finished": true,
            "networkRequestTime": 82.86600017547607,
            "sessionTargetType": "page",
            "rendererStartTime": 82.47799968719482,
            "mimeType": "text/javascript"
          },
          {
            "rendererStartTime": 82.69000005722046,
            "statusCode": 200,
            "experimentalFromMainFrame": true,
            "resourceType": "Script",
            "entity": "Bootstrap CDN",
            "networkRequestTime": 83.13000011444092,
            "priority": "High",
            "mimeType": "application/javascript",
            "finished": true,
            "transferSize": 12185,
            "networkEndTime": 96.05599975585938,
            "resourceSize": 39680,
            "sessionTargetType": "page",
            "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js",
            "protocol": "h2"
          },
          {
            "finished": true,
            "resourceSize": 523057,
            "resourceType": "Image",
            "experimentalFromMainFrame": true,
            "transferSize": 523774,
            "mimeType": "image/jpeg",
            "priority": "High",
            "networkEndTime": 238.17700004577637,
            "entity": "GitHub",
            "rendererStartTime": 82.91199970245361,
            "protocol": "h2",
            "networkRequestTime": 83.40100002288818,
            "statusCode": 200,
            "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-1.jpg",
            "sessionTargetType": "page"
          },
          {
            "resourceType": "Image",
            "networkRequestTime": 83.63700008392334,
            "entity": "GitHub",
            "rendererStartTime": 83.21399974822998,
            "resourceSize": 473937,
            "finished": true,
            "networkEndTime": 223.15199995040894,
            "protocol": "h2",
            "transferSize": 474633,
            "priority": "Medium",
            "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-2.jpg",
            "experimentalFromMainFrame": true,
            "mimeType": "image/jpeg",
            "statusCode": 200,
            "sessionTargetType": "page"
          },
          {
            "statusCode": 200,
            "networkRequestTime": 125.65899991989136,
            "protocol": "h2",
            "entity": "GitHub",
            "networkEndTime": 171.24300003051758,
            "resourceType": "Image",
            "finished": true,
            "transferSize": 50653,
            "rendererStartTime": 83.51999998092651,
            "url": "https://jxbang94.github.io/Website-main/assets/img/late.jpg",
            "sessionTargetType": "page",
            "resourceSize": 49959,
            "mimeType": "image/jpeg",
            "experimentalFromMainFrame": true,
            "priority": "High"
          },
          {
            "url": "https://jxbang94.github.io/Website-main/assets/img/support.jpg",
            "networkEndTime": 186.49900007247925,
            "transferSize": 93723,
            "mimeType": "image/jpeg",
            "priority": "High",
            "experimentalFromMainFrame": true,
            "networkRequestTime": 125.81599950790405,
            "resourceSize": 93007,
            "sessionTargetType": "page",
            "protocol": "h2",
            "entity": "GitHub",
            "rendererStartTime": 83.65199995040894,
            "finished": true,
            "statusCode": 200,
            "resourceType": "Image"
          },
          {
            "rendererStartTime": 130.48099994659424,
            "sessionTargetType": "page",
            "protocol": "h2",
            "transferSize": 18925,
            "resourceType": "Font",
            "networkRequestTime": 130.94499969482422,
            "mimeType": "font/woff2",
            "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/fonts/glyphicons-halflings-regular.woff2",
            "finished": true,
            "priority": "VeryHigh",
            "statusCode": 200,
            "resourceSize": 18028,
            "experimentalFromMainFrame": true,
            "entity": "Bootstrap CDN",
            "networkEndTime": 199.44000005722046
          }
        ]
      }
    },
    "uses-text-compression": {
      "id": "uses-text-compression",
      "title": "Enable text compression",
      "description": "Text-based resources should be served with compression (gzip, deflate or brotli) to minimize total network bytes. [Learn more about text compression](https://developer.chrome.com/docs/lighthouse/performance/uses-text-compression/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "type": "opportunity",
        "overallSavingsMs": 0,
        "headings": [],
        "debugData": {
          "metricSavings": {
            "FCP": 0,
            "LCP": 0
          },
          "type": "debugdata"
        },
        "sortedBy": [
          "wastedBytes"
        ],
        "overallSavingsBytes": 0,
        "items": []
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "doctype": {
      "id": "doctype",
      "title": "Page has the HTML doctype",
      "description": "Specifying a doctype prevents the browser from switching to quirks-mode. [Learn more about the doctype declaration](https://developer.chrome.com/docs/lighthouse/best-practices/doctype/).",
      "score": 1,
      "scoreDisplayMode": "binary"
    },
    "unsized-images": {
      "id": "unsized-images",
      "title": "Image elements do not have explicit `width` and `height`",
      "description": "Set an explicit width and height on image elements to reduce layout shifts and improve CLS. [Learn how to set image dimensions](https://web.dev/optimize-cls/#images-without-dimensions)",
      "score": 0,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [
          {
            "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-1.jpg",
            "node": {
              "snippet": "<img src=\"assets/img/carousel-1.jpg\" alt=\"Image of keyboard, controllers, mouse, smartphone, and headphones on a des…\">",
              "type": "node",
              "lhId": "1-9-IMG",
              "path": "1,HTML,1,BODY,1,DIV,3,DIV,0,DIV,0,IMG",
              "boundingRect": {
                "top": 52,
                "width": 980,
                "right": 980,
                "left": 0,
                "bottom": 652,
                "height": 600
              },
              "nodeLabel": "Image of keyboard, controllers, mouse, smartphone, and headphones on a desk.",
              "selector": "div#myCarousel > div.carousel-inner > div.item > img"
            }
          }
        ],
        "headings": [
          {
            "key": "node",
            "valueType": "node"
          },
          {
            "key": "url",
            "label": "URL",
            "valueType": "url"
          }
        ],
        "type": "table"
      }
    },
    "image-size-responsive": {
      "id": "image-size-responsive",
      "title": "Serves images with appropriate resolution",
      "description": "Image natural dimensions should be proportional to the display size and the pixel ratio to maximize image clarity. [Learn how to provide responsive images](https://web.dev/serve-responsive-images/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "type": "table",
        "headings": []
      }
    },
    "cumulative-layout-shift": {
      "id": "cumulative-layout-shift",
      "title": "Cumulative Layout Shift",
      "description": "Cumulative Layout Shift measures the movement of visible elements within the viewport. [Learn more about the Cumulative Layout Shift metric](https://web.dev/cls/).",
      "score": 0.4,
      "scoreDisplayMode": "numeric",
      "displayValue": "0.294",
      "details": {
        "items": [
          {
            "cumulativeLayoutShiftMainFrame": 0.2944306790816325
          }
        ],
        "type": "debugdata"
      },
      "numericValue": 0.2944306790816325,
      "numericUnit": "unitless"
    },
    "td-has-header": {
      "id": "td-has-header",
      "title": "`<td>` elements in a large `<table>` have one or more table headers.",
      "description": "Screen readers have features to make navigating tables easier. Ensuring that `<td>` elements in a large table (3 or more cells in width and height) have an associated table header may improve the experience for screen reader users. [Learn more about table headers](https://dequeuniversity.com/rules/axe/4.7/td-has-header).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "total-blocking-time": {
      "id": "total-blocking-time",
      "title": "Total Blocking Time",
      "description": "Sum of all time periods between FCP and Time to Interactive, when task length exceeded 50ms, expressed in milliseconds. [Learn more about the Total Blocking Time metric](https://developer.chrome.com/docs/lighthouse/performance/lighthouse-total-blocking-time/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "0 ms",
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "aria-allowed-attr": {
      "id": "aria-allowed-attr",
      "title": "`[aria-*]` attributes match their roles",
      "description": "Each ARIA `role` supports a specific subset of `aria-*` attributes. Mismatching these invalidates the `aria-*` attributes. [Learn how to match ARIA attributes to their roles](https://dequeuniversity.com/rules/axe/4.7/aria-allowed-attr).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "largest-contentful-paint": {
      "id": "largest-contentful-paint",
      "title": "Largest Contentful Paint",
      "description": "Largest Contentful Paint marks the time at which the largest text or image is painted. [Learn more about the Largest Contentful Paint metric](https://developer.chrome.com/docs/lighthouse/performance/lighthouse-largest-contentful-paint/)",
      "score": 0.03,
      "scoreDisplayMode": "numeric",
      "displayValue": "7.6 s",
      "numericValue": 7621,
      "numericUnit": "millisecond"
    },
    "speed-index": {
      "id": "speed-index",
      "title": "Speed Index",
      "description": "Speed Index shows how quickly the contents of a page are visibly populated. [Learn more about the Speed Index metric](https://developer.chrome.com/docs/lighthouse/performance/speed-index/).",
      "score": 0.99,
      "scoreDisplayMode": "numeric",
      "displayValue": "2.0 s",
      "numericValue": 1985.5,
      "numericUnit": "millisecond"
    },
    "notification-on-start": {
      "id": "notification-on-start",
      "title": "Avoids requesting the notification permission on page load",
      "description": "Users are mistrustful of or confused by sites that request to send notifications without context. Consider tying the request to user gestures instead. [Learn more about responsibly getting permission for notifications](https://developer.chrome.com/docs/lighthouse/best-practices/notification-on-start/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "items": [],
        "headings": []
      }
    },
    "aria-roles": {
      "id": "aria-roles",
      "title": "`[role]` values are valid",
      "description": "ARIA roles must have valid values in order to perform their intended accessibility functions. [Learn more about valid ARIA roles](https://dequeuniversity.com/rules/axe/4.7/aria-roles).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "headings": [],
        "type": "table"
      }
    },
    "uses-optimized-images": {
      "id": "uses-optimized-images",
      "title": "Efficiently encode images",
      "description": "Optimized images load faster and consume less cellular data. [Learn how to efficiently encode images](https://developer.chrome.com/docs/lighthouse/performance/uses-optimized-images/).",
      "score": 0.66,
      "scoreDisplayMode": "numeric",
      "displayValue": "Potential savings of 105 KiB",
      "details": {
        "type": "opportunity",
        "overallSavingsMs": 500,
        "debugData": {
          "type": "debugdata",
          "metricSavings": {
            "FCP": 0,
            "LCP": 500
          }
        },
        "overallSavingsBytes": 107288,
        "sortedBy": [
          "wastedBytes"
        ],
        "items": [
          {
            "node": {
              "nodeLabel": "Image",
              "path": "1,HTML,1,BODY,1,DIV,3,DIV,1,DIV,0,IMG",
              "type": "node",
              "lhId": "1-23-IMG",
              "snippet": "<img src=\"assets/img/carousel-2.jpg\" alt=\"Image\">",
              "boundingRect": {
                "left": 0,
                "height": 0,
                "right": 0,
                "bottom": 0,
                "top": 0,
                "width": 0
              },
              "selector": "div#myCarousel > div.carousel-inner > div.item > img"
            },
            "wastedBytes": 91683,
            "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-2.jpg",
            "totalBytes": 473937,
            "fromProtocol": true,
            "isCrossOrigin": false
          },
          {
            "wastedBytes": 9879,
            "fromProtocol": true,
            "url": "https://jxbang94.github.io/Website-main/assets/img/support.jpg",
            "node": {
              "type": "node",
              "snippet": "<img src=\"assets/img/support.jpg\" class=\"img-responsive\" style=\"width:100%\" height=\"400\" alt=\"image of a few people in a circle with hands.\">",
              "selector": "div.container > div.row > div.col-sm-4 > img.img-responsive",
              "nodeLabel": "image of a few people in a circle with hands.",
              "path": "1,HTML,1,BODY,3,MAIN,3,DIV,0,DIV,0,DIV,1,IMG",
              "boundingRect": {
                "bottom": 1273,
                "height": 147,
                "left": 130,
                "right": 350,
                "top": 1127,
                "width": 220
              },
              "lhId": "1-25-IMG"
            },
            "isCrossOrigin": false,
            "totalBytes": 93007
          },
          {
            "url": "https://jxbang94.github.io/Website-main/assets/img/late.jpg",
            "node": {
              "nodeLabel": "drawing of boy playing video games on a couch",
              "selector": "div.container > div.row > div.col-sm-4 > img.img-responsive",
              "path": "1,HTML,1,BODY,3,MAIN,0,DIV,0,DIV,2,DIV,0,IMG",
              "boundingRect": {
                "left": 380,
                "height": 165,
                "right": 600,
                "top": 713,
                "width": 220,
                "bottom": 878
              },
              "snippet": "<img src=\"assets/img/late.jpg\" class=\"img-responsive\" style=\"width:100%\" height=\"400\" alt=\"drawing of boy playing video games on a couch\">",
              "lhId": "1-24-IMG",
              "type": "node"
            },
            "fromProtocol": true,
            "wastedBytes": 5726,
            "isCrossOrigin": false,
            "totalBytes": 49959
          }
        ],
        "headings": [
          {
            "valueType": "node",
            "key": "node"
          },
          {
            "key": "url",
            "valueType": "url",
            "label": "URL"
          },
          {
            "label": "Resource Size",
            "valueType": "bytes",
            "key": "totalBytes"
          },
          {
            "key": "wastedBytes",
            "label": "Potential Savings",
            "valueType": "bytes"
          }
        ]
      },
      "warnings": [],
      "numericValue": 500,
      "numericUnit": "millisecond"
    },
    "table-duplicate-name": {
      "id": "table-duplicate-name",
      "title": "Tables have different content in the summary attribute and `<caption>`.",
      "description": "The summary attribute should describe the table structure, while `<caption>` should have the onscreen title. Accurate table mark-up helps users of screen readers. [Learn more about summary and caption](https://dequeuniversity.com/rules/axe/4.7/table-duplicate-name).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "splash-screen": {
      "id": "splash-screen",
      "title": "Is not configured for a custom splash screen",
      "description": "A themed splash screen ensures a high-quality experience when users launch your app from their homescreens. [Learn more about splash screens](https://developer.chrome.com/docs/lighthouse/pwa/splash-screen/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "explanation": "Failures: No manifest was fetched.",
      "details": {
        "items": [
          {
            "isParseFailure": true,
            "failures": [
              "No manifest was fetched"
            ],
            "parseFailureReason": "No manifest was fetched"
          }
        ],
        "type": "debugdata"
      }
    },
    "aria-dialog-name": {
      "id": "aria-dialog-name",
      "title": "Elements with `role=\"dialog\"` or `role=\"alertdialog\"` have accessible names.",
      "description": "ARIA dialog elements without accessible names may prevent screen readers users from discerning the purpose of these elements. [Learn how to make ARIA dialog elements more accessible](https://dequeuniversity.com/rules/axe/4.7/aria-dialog-name).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "definition-list": {
      "id": "definition-list",
      "title": "`<dl>`'s contain only properly-ordered `<dt>` and `<dd>` groups, `<script>`, `<template>` or `<div>` elements.",
      "description": "When definition lists are not properly marked up, screen readers may produce confusing or inaccurate output. [Learn how to structure definition lists correctly](https://dequeuniversity.com/rules/axe/4.7/definition-list).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "landmark-one-main": {
      "id": "landmark-one-main",
      "title": "Document has a main landmark.",
      "description": "One main landmark helps screen reader users navigate a web page. [Learn more about landmarks](https://dequeuniversity.com/rules/axe/4.7/landmark-one-main).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "video-caption": {
      "id": "video-caption",
      "title": "`<video>` elements contain a `<track>` element with `[kind=\"captions\"]`",
      "description": "When a video provides a caption it is easier for deaf and hearing impaired users to access its information. [Learn more about video captions](https://dequeuniversity.com/rules/axe/4.7/video-caption).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "third-party-facades": {
      "id": "third-party-facades",
      "title": "Lazy load third-party resources with facades",
      "description": "Some third-party embeds can be lazy loaded. Consider replacing them with a facade until they are required. [Learn how to defer third-parties with a facade](https://developer.chrome.com/docs/lighthouse/performance/third-party-facades/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "logical-tab-order": {
      "id": "logical-tab-order",
      "title": "The page has a logical tab order",
      "description": "Tabbing through the page follows the visual layout. Users cannot focus elements that are offscreen. [Learn more about logical tab ordering](https://developer.chrome.com/docs/lighthouse/accessibility/logical-tab-order/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "plugins": {
      "id": "plugins",
      "title": "Document avoids plugins",
      "description": "Search engines can't index plugin content, and many devices restrict plugins or don't support them. [Learn more about avoiding plugins](https://developer.chrome.com/docs/lighthouse/seo/plugins/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "headings": [],
        "type": "table"
      }
    },
    "list": {
      "id": "list",
      "title": "Lists contain only `<li>` elements and script supporting elements (`<script>` and `<template>`).",
      "description": "Screen readers have a specific way of announcing lists. Ensuring proper list structure aids screen reader output. [Learn more about proper list structure](https://dequeuniversity.com/rules/axe/4.7/list).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "headings": [],
        "items": []
      }
    },
    "largest-contentful-paint-element": {
      "id": "largest-contentful-paint-element",
      "title": "Largest Contentful Paint element",
      "description": "This is the largest contentful element painted within the viewport. [Learn more about the Largest Contentful Paint element](https://developer.chrome.com/docs/lighthouse/performance/lighthouse-largest-contentful-paint/)",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "7,620 ms",
      "details": {
        "type": "list",
        "items": [
          {
            "type": "table",
            "headings": [
              {
                "key": "node",
                "label": "Element",
                "valueType": "node"
              }
            ],
            "items": [
              {
                "node": {
                  "boundingRect": {
                    "top": 52,
                    "height": 600,
                    "right": 980,
                    "bottom": 652,
                    "left": 0,
                    "width": 980
                  },
                  "snippet": "<img src=\"assets/img/carousel-1.jpg\" alt=\"Image of keyboard, controllers, mouse, smartphone, and headphones on a des…\">",
                  "lhId": "page-0-IMG",
                  "selector": "div#myCarousel > div.carousel-inner > div.item > img",
                  "path": "1,HTML,1,BODY,1,DIV,3,DIV,0,DIV,0,IMG",
                  "nodeLabel": "Image of keyboard, controllers, mouse, smartphone, and headphones on a desk.",
                  "type": "node"
                }
              }
            ]
          },
          {
            "headings": [
              {
                "label": "Phase",
                "key": "phase",
                "valueType": "text"
              },
              {
                "valueType": "text",
                "label": "% of LCP",
                "key": "percent"
              },
              {
                "key": "timing",
                "label": "Timing",
                "valueType": "ms"
              }
            ],
            "items": [
              {
                "timing": 639,
                "percent": "8%",
                "phase": "TTFB"
              },
              {
                "percent": "23%",
                "timing": 1747.9137339378503,
                "phase": "Load Delay"
              },
              {
                "timing": 4424.65966267581,
                "percent": "58%",
                "phase": "Load Time"
              },
              {
                "timing": 809.4266033863396,
                "percent": "11%",
                "phase": "Render Delay"
              }
            ],
            "type": "table"
          }
        ]
      }
    },
    "uses-long-cache-ttl": {
      "id": "uses-long-cache-ttl",
      "title": "Serve static assets with an efficient cache policy",
      "description": "A long cache lifetime can speed up repeat visits to your page. [Learn more about efficient cache policies](https://developer.chrome.com/docs/lighthouse/performance/uses-long-cache-ttl/).",
      "score": 0.03,
      "scoreDisplayMode": "numeric",
      "displayValue": "4 resources found",
      "details": {
        "skipSumming": [
          "cacheLifetimeMs"
        ],
        "headings": [
          {
            "valueType": "url",
            "label": "URL",
            "key": "url"
          },
          {
            "label": "Cache TTL",
            "valueType": "ms",
            "key": "cacheLifetimeMs",
            "displayUnit": "duration"
          },
          {
            "displayUnit": "kb",
            "valueType": "bytes",
            "key": "totalBytes",
            "granularity": 1,
            "label": "Transfer Size"
          }
        ],
        "summary": {
          "wastedBytes": 1047551.0833333333
        },
        "type": "table",
        "items": [
          {
            "debugData": {
              "max-age": 600,
              "type": "debugdata"
            },
            "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-1.jpg",
            "totalBytes": 523774,
            "cacheLifetimeMs": 600000,
            "cacheHitProbability": 0.08333333333333333,
            "wastedBytes": 480126.1666666666
          },
          {
            "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-2.jpg",
            "wastedBytes": 435080.25,
            "totalBytes": 474633,
            "cacheHitProbability": 0.08333333333333333,
            "debugData": {
              "type": "debugdata",
              "max-age": 600
            },
            "cacheLifetimeMs": 600000
          },
          {
            "totalBytes": 93723,
            "debugData": {
              "type": "debugdata",
              "max-age": 600
            },
            "url": "https://jxbang94.github.io/Website-main/assets/img/support.jpg",
            "wastedBytes": 85912.75,
            "cacheHitProbability": 0.08333333333333333,
            "cacheLifetimeMs": 600000
          },
          {
            "totalBytes": 50653,
            "url": "https://jxbang94.github.io/Website-main/assets/img/late.jpg",
            "cacheHitProbability": 0.08333333333333333,
            "cacheLifetimeMs": 600000,
            "debugData": {
              "type": "debugdata",
              "max-age": 600
            },
            "wastedBytes": 46431.916666666664
          }
        ],
        "sortedBy": [
          "totalBytes"
        ]
      },
      "numericValue": 1047551.0833333333,
      "numericUnit": "byte"
    },
    "geolocation-on-start": {
      "id": "geolocation-on-start",
      "title": "Avoids requesting the geolocation permission on page load",
      "description": "Users are mistrustful of or confused by sites that request their location without context. Consider tying the request to a user action instead. [Learn more about the geolocation permission](https://developer.chrome.com/docs/lighthouse/best-practices/geolocation-on-start/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "type": "table",
        "items": []
      }
    },
    "legacy-javascript": {
      "id": "legacy-javascript",
      "title": "Avoid serving legacy JavaScript to modern browsers",
      "description": "Polyfills and transforms enable legacy browsers to use new JavaScript features. However, many aren't necessary for modern browsers. For your bundled JavaScript, adopt a modern script deployment strategy using module/nomodule feature detection to reduce the amount of code shipped to modern browsers, while retaining support for legacy browsers. [Learn how to use modern JavaScript](https://web.dev/publish-modern-javascript/)",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "headings": [],
        "type": "opportunity",
        "sortedBy": [
          "wastedBytes"
        ],
        "items": [],
        "overallSavingsBytes": 0,
        "debugData": {
          "type": "debugdata",
          "metricSavings": {
            "FCP": 0,
            "LCP": 0
          }
        },
        "overallSavingsMs": 0
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "aria-progressbar-name": {
      "id": "aria-progressbar-name",
      "title": "ARIA `progressbar` elements have accessible names",
      "description": "When a `progressbar` element doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn how to label `progressbar` elements](https://dequeuniversity.com/rules/axe/4.7/aria-progressbar-name).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "render-blocking-resources": {
      "id": "render-blocking-resources",
      "title": "Eliminate render-blocking resources",
      "description": "Resources are blocking the first paint of your page. Consider delivering critical JS/CSS inline and deferring all non-critical JS/styles. [Learn how to eliminate render-blocking resources](https://developer.chrome.com/docs/lighthouse/performance/render-blocking-resources/).",
      "score": 0.46,
      "scoreDisplayMode": "numeric",
      "displayValue": "Potential savings of 1,060 ms",
      "details": {
        "headings": [
          {
            "key": "url",
            "label": "URL",
            "valueType": "url"
          },
          {
            "valueType": "bytes",
            "label": "Transfer Size",
            "key": "totalBytes"
          },
          {
            "key": "wastedMs",
            "valueType": "timespanMs",
            "label": "Potential Savings"
          }
        ],
        "items": [
          {
            "totalBytes": 21238,
            "wastedMs": 909,
            "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css"
          },
          {
            "wastedMs": 1051,
            "url": "https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js",
            "totalBytes": 31425
          },
          {
            "totalBytes": 12185,
            "wastedMs": 150,
            "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"
          }
        ],
        "type": "opportunity",
        "overallSavingsMs": 1064
      },
      "numericValue": 1064,
      "numericUnit": "millisecond"
    },
    "server-response-time": {
      "id": "server-response-time",
      "title": "Initial server response time was short",
      "description": "Keep the server response time for the main document short because all other requests depend on it. [Learn more about the Time to First Byte metric](https://developer.chrome.com/docs/lighthouse/performance/time-to-first-byte/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "displayValue": "Root document took 30 ms",
      "details": {
        "items": [
          {
            "responseTime": 32,
            "url": "https://jxbang94.github.io/Website-main/"
          }
        ],
        "type": "opportunity",
        "headings": [
          {
            "label": "URL",
            "key": "url",
            "valueType": "url"
          },
          {
            "valueType": "timespanMs",
            "label": "Time Spent",
            "key": "responseTime"
          }
        ],
        "overallSavingsMs": 0
      },
      "numericValue": 32,
      "numericUnit": "millisecond"
    },
    "image-aspect-ratio": {
      "id": "image-aspect-ratio",
      "title": "Displays images with incorrect aspect ratio",
      "description": "Image display dimensions should match natural aspect ratio. [Learn more about image aspect ratio](https://developer.chrome.com/docs/lighthouse/best-practices/image-aspect-ratio/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [
          {
            "valueType": "node",
            "key": "node"
          },
          {
            "label": "URL",
            "valueType": "url",
            "key": "url"
          },
          {
            "label": "Aspect Ratio (Displayed)",
            "valueType": "text",
            "key": "displayedAspectRatio"
          },
          {
            "key": "actualAspectRatio",
            "valueType": "text",
            "label": "Aspect Ratio (Actual)"
          }
        ],
        "items": [
          {
            "doRatiosMatch": false,
            "displayedAspectRatio": "980 x 600\n        (1.63)",
            "node": {
              "nodeLabel": "Image of keyboard, controllers, mouse, smartphone, and headphones on a desk.",
              "lhId": "1-9-IMG",
              "snippet": "<img src=\"assets/img/carousel-1.jpg\" alt=\"Image of keyboard, controllers, mouse, smartphone, and headphones on a des…\">",
              "type": "node",
              "boundingRect": {
                "right": 980,
                "left": 0,
                "bottom": 652,
                "width": 980,
                "height": 600,
                "top": 52
              },
              "selector": "div#myCarousel > div.carousel-inner > div.item > img",
              "path": "1,HTML,1,BODY,1,DIV,3,DIV,0,DIV,0,IMG"
            },
            "actualAspectRatio": "2400 x 1600\n        (1.50)",
            "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-1.jpg"
          }
        ],
        "type": "table"
      }
    },
    "select-name": {
      "id": "select-name",
      "title": "Select elements have associated label elements.",
      "description": "Form elements without effective labels can create frustrating experiences for screen reader users. [Learn more about the `select` element](https://dequeuniversity.com/rules/axe/4.7/select-name).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "html-lang-valid": {
      "id": "html-lang-valid",
      "title": "`<html>` element has a valid value for its `[lang]` attribute",
      "description": "Specifying a valid [BCP 47 language](https://www.w3.org/International/questions/qa-choosing-language-tags#question) helps screen readers announce text properly. [Learn how to use the `lang` attribute](https://dequeuniversity.com/rules/axe/4.7/html-lang-valid).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "type": "table",
        "headings": []
      }
    },
    "js-libraries": {
      "id": "js-libraries",
      "title": "Detected JavaScript libraries",
      "description": "All front-end JavaScript libraries detected on the page. [Learn more about this JavaScript library detection diagnostic audit](https://developer.chrome.com/docs/lighthouse/best-practices/js-libraries/).",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "items": [
          {
            "name": "Bootstrap",
            "version": "3.4.1",
            "npm": "bootstrap"
          },
          {
            "name": "jQuery",
            "version": "3.7.1",
            "npm": "jquery"
          }
        ],
        "type": "table",
        "debugData": {
          "type": "debugdata",
          "stacks": [
            {
              "id": "bootstrap",
              "version": "3.4.1"
            },
            {
              "id": "jquery",
              "version": "3.7.1"
            },
            {
              "id": "jquery-fast"
            }
          ]
        },
        "headings": [
          {
            "valueType": "text",
            "key": "name",
            "label": "Name"
          },
          {
            "label": "Version",
            "key": "version",
            "valueType": "text"
          }
        ]
      }
    },
    "image-redundant-alt": {
      "id": "image-redundant-alt",
      "title": "Image elements do not have `[alt]` attributes that are redundant text.",
      "description": "Informative elements should aim for short, descriptive alternative text. Alternative text that is exactly the same as the text adjacent to the link or image is potentially confusing for screen reader users, because the text will be read twice. [Learn more about the `alt` attribute](https://dequeuniversity.com/rules/axe/4.7/image-redundant-alt).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "type": "table",
        "headings": []
      }
    },
    "lcp-lazy-loaded": {
      "id": "lcp-lazy-loaded",
      "title": "Largest Contentful Paint image was not lazily loaded",
      "description": "Above-the-fold images that are lazily loaded render later in the page lifecycle, which can delay the largest contentful paint. [Learn more about optimal lazy loading](https://web.dev/lcp-lazy-loading/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "headings": [
          {
            "valueType": "node",
            "key": "node",
            "label": "Element"
          }
        ],
        "items": [
          {
            "node": {
              "snippet": "<img src=\"assets/img/carousel-1.jpg\" alt=\"Image of keyboard, controllers, mouse, smartphone, and headphones on a des…\">",
              "path": "1,HTML,1,BODY,1,DIV,3,DIV,0,DIV,0,IMG",
              "selector": "div#myCarousel > div.carousel-inner > div.item > img",
              "lhId": "1-9-IMG",
              "nodeLabel": "Image of keyboard, controllers, mouse, smartphone, and headphones on a desk.",
              "type": "node",
              "boundingRect": {
                "width": 980,
                "top": 52,
                "bottom": 652,
                "right": 980,
                "left": 0,
                "height": 600
              }
            }
          }
        ]
      }
    },
    "custom-controls-labels": {
      "id": "custom-controls-labels",
      "title": "Custom controls have associated labels",
      "description": "Custom interactive controls have associated labels, provided by aria-label or aria-labelledby. [Learn more about custom controls and labels](https://developer.chrome.com/docs/lighthouse/accessibility/custom-controls-labels/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "final-screenshot": {
      "id": "final-screenshot",
      "title": "Final Screenshot",
      "description": "The last screenshot captured of the pageload.",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "data": "data:image/jpeg;base64,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",
        "timing": 271,
        "type": "screenshot",
        "timestamp": 3872842980084
      }
    },
    "duplicate-id-aria": {
      "id": "duplicate-id-aria",
      "title": "ARIA IDs are unique",
      "description": "The value of an ARIA ID must be unique to prevent other instances from being overlooked by assistive technologies. [Learn how to fix duplicate ARIA IDs](https://dequeuniversity.com/rules/axe/4.7/duplicate-id-aria).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "type": "table",
        "headings": []
      }
    },
    "use-landmarks": {
      "id": "use-landmarks",
      "title": "HTML5 landmark elements are used to improve navigation",
      "description": "Landmark elements (`<main>`, `<nav>`, etc.) are used to improve the keyboard navigation of the page for assistive technology. [Learn more about landmark elements](https://developer.chrome.com/docs/lighthouse/accessibility/use-landmarks/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "viewport": {
      "id": "viewport",
      "title": "Does not have a `<meta name=\"viewport\">` tag with `width` or `initial-scale`",
      "description": "A `<meta name=\"viewport\">` not only optimizes your app for mobile screen sizes, but also prevents [a 300 millisecond delay to user input](https://developer.chrome.com/blog/300ms-tap-delay-gone-away/). [Learn more about using the viewport meta tag](https://developer.chrome.com/docs/lighthouse/pwa/viewport/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "explanation": "No `<meta name=\"viewport\">` tag found"
    },
    "long-tasks": {
      "id": "long-tasks",
      "title": "Avoid long main-thread tasks",
      "description": "Lists the longest tasks on the main thread, useful for identifying worst contributors to input delay. [Learn how to avoid long main-thread tasks](https://web.dev/long-tasks-devtools/)",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "1 long task found",
      "details": {
        "sortedBy": [
          "duration"
        ],
        "items": [
          {
            "url": "https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js",
            "duration": 50,
            "startTime": 2085.5
          }
        ],
        "debugData": {
          "type": "debugdata",
          "tasks": [
            {
              "startTime": 2085.5,
              "duration": 50,
              "urlIndex": 0,
              "scriptEvaluation": 0,
              "other": 50
            }
          ],
          "urls": [
            "https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"
          ]
        },
        "type": "table",
        "headings": [
          {
            "key": "url",
            "valueType": "url",
            "label": "URL"
          },
          {
            "valueType": "ms",
            "label": "Start Time",
            "key": "startTime",
            "granularity": 1
          },
          {
            "key": "duration",
            "label": "Duration",
            "granularity": 1,
            "valueType": "ms"
          }
        ],
        "skipSumming": [
          "startTime"
        ]
      }
    },
    "target-size": {
      "id": "target-size",
      "title": "Touch targets have sufficient size and spacing.",
      "description": "Touch targets with sufficient size and spacing help users who may have difficulty targeting small controls to activate the targets. [Learn more about touch targets](https://dequeuniversity.com/rules/axe/4.7/target-size).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "skip-link": {
      "id": "skip-link",
      "title": "Skip links are focusable.",
      "description": "Including a skip link can help users skip to the main content to save time. [Learn more about skip links](https://dequeuniversity.com/rules/axe/4.7/skip-link).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "user-timings": {
      "id": "user-timings",
      "title": "User Timing marks and measures",
      "description": "Consider instrumenting your app with the User Timing API to measure your app's real-world performance during key user experiences. [Learn more about User Timing marks](https://developer.chrome.com/docs/lighthouse/performance/user-timings/).",
      "score": null,
      "scoreDisplayMode": "notApplicable",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "aria-treeitem-name": {
      "id": "aria-treeitem-name",
      "title": "ARIA `treeitem` elements have accessible names",
      "description": "When a `treeitem` element doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn more about labeling `treeitem` elements](https://dequeuniversity.com/rules/axe/4.7/aria-treeitem-name).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "mainthread-work-breakdown": {
      "id": "mainthread-work-breakdown",
      "title": "Minimizes main-thread work",
      "description": "Consider reducing the time spent parsing, compiling and executing JS. You may find delivering smaller JS payloads helps with this. [Learn how to minimize main-thread work](https://developer.chrome.com/docs/lighthouse/performance/mainthread-work-breakdown/)",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "0.4 s",
      "details": {
        "headings": [
          {
            "label": "Category",
            "key": "groupLabel",
            "valueType": "text"
          },
          {
            "key": "duration",
            "label": "Time Spent",
            "granularity": 1,
            "valueType": "ms"
          }
        ],
        "sortedBy": [
          "duration"
        ],
        "type": "table",
        "items": [
          {
            "group": "other",
            "groupLabel": "Other",
            "duration": 132.924
          },
          {
            "duration": 97.46799999999996,
            "groupLabel": "Script Evaluation",
            "group": "scriptEvaluation"
          },
          {
            "group": "styleLayout",
            "groupLabel": "Style & Layout",
            "duration": 65.56
          },
          {
            "groupLabel": "Parse HTML & CSS",
            "duration": 23.732000000000006,
            "group": "parseHTML"
          },
          {
            "groupLabel": "Rendering",
            "duration": 18.239999999999995,
            "group": "paintCompositeRender"
          },
          {
            "group": "scriptParseCompile",
            "duration": 12.128,
            "groupLabel": "Script Parsing & Compilation"
          }
        ]
      },
      "numericValue": 350.052,
      "numericUnit": "millisecond"
    },
    "link-name": {
      "id": "link-name",
      "title": "Links have a discernible name",
      "description": "Link text (and alternate text for images, when used as links) that is discernible, unique, and focusable improves the navigation experience for screen reader users. [Learn how to make links accessible](https://dequeuniversity.com/rules/axe/4.7/link-name).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "type": "table",
        "items": []
      }
    },
    "object-alt": {
      "id": "object-alt",
      "title": "`<object>` elements have alternate text",
      "description": "Screen readers cannot translate non-text content. Adding alternate text to `<object>` elements helps screen readers convey meaning to users. [Learn more about alt text for `object` elements](https://dequeuniversity.com/rules/axe/4.7/object-alt).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "aria-allowed-role": {
      "id": "aria-allowed-role",
      "title": "Values assigned to `role=\"\"` are valid ARIA roles.",
      "description": "ARIA `role`s enable assistive technologies to know the role of each element on the web page. If the `role` values are misspelled, not existing ARIA `role` values, or abstract roles, then the purpose of the element will not be communicated to users of assistive technologies. [Learn more about ARIA roles](https://dequeuniversity.com/rules/axe/4.7/aria-allowed-roles).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "type": "table",
        "items": []
      }
    },
    "font-size": {
      "id": "font-size",
      "title": "Document doesn't use legible font sizes",
      "description": "Font sizes less than 12px are too small to be legible and require mobile visitors to “pinch to zoom” in order to read. Strive to have >60% of page text ≥12px. [Learn more about legible font sizes](https://developer.chrome.com/docs/lighthouse/seo/font-size/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "explanation": "Text is illegible because there's no viewport meta tag optimized for mobile screens."
    },
    "csp-xss": {
      "id": "csp-xss",
      "title": "Ensure CSP is effective against XSS attacks",
      "description": "A strong Content Security Policy (CSP) significantly reduces the risk of cross-site scripting (XSS) attacks. [Learn how to use a CSP to prevent XSS](https://developer.chrome.com/docs/lighthouse/best-practices/csp-xss/)",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "items": [
          {
            "severity": "High",
            "description": "No CSP found in enforcement mode"
          }
        ],
        "type": "table",
        "headings": [
          {
            "subItemsHeading": {
              "key": "description"
            },
            "valueType": "text",
            "label": "Description",
            "key": "description"
          },
          {
            "valueType": "code",
            "key": "directive",
            "subItemsHeading": {
              "key": "directive"
            },
            "label": "Directive"
          },
          {
            "key": "severity",
            "subItemsHeading": {
              "key": "severity"
            },
            "label": "Severity",
            "valueType": "text"
          }
        ]
      }
    },
    "td-headers-attr": {
      "id": "td-headers-attr",
      "title": "Cells in a `<table>` element that use the `[headers]` attribute refer to table cells within the same table.",
      "description": "Screen readers have features to make navigating tables easier. Ensuring `<td>` cells using the `[headers]` attribute only refer to other cells in the same table may improve the experience for screen reader users. [Learn more about the `headers` attribute](https://dequeuniversity.com/rules/axe/4.7/td-headers-attr).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "accesskeys": {
      "id": "accesskeys",
      "title": "`[accesskey]` values are unique",
      "description": "Access keys let users quickly focus a part of the page. For proper navigation, each access key must be unique. [Learn more about access keys](https://dequeuniversity.com/rules/axe/4.7/accesskeys).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "max-potential-fid": {
      "id": "max-potential-fid",
      "title": "Max Potential First Input Delay",
      "description": "The maximum potential First Input Delay that your users could experience is the duration of the longest task. [Learn more about the Maximum Potential First Input Delay metric](https://developer.chrome.com/docs/lighthouse/performance/lighthouse-max-potential-fid/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "50 ms",
      "numericValue": 50,
      "numericUnit": "millisecond"
    },
    "unused-javascript": {
      "id": "unused-javascript",
      "title": "Reduce unused JavaScript",
      "description": "Reduce unused JavaScript and defer loading scripts until they are required to decrease bytes consumed by network activity. [Learn how to reduce unused JavaScript](https://developer.chrome.com/docs/lighthouse/performance/unused-javascript/).",
      "score": 0.88,
      "scoreDisplayMode": "numeric",
      "displayValue": "Potential savings of 20 KiB",
      "details": {
        "items": [
          {
            "wastedPercent": 66.45379456890545,
            "url": "https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js",
            "wastedBytes": 20883,
            "totalBytes": 31425
          }
        ],
        "debugData": {
          "type": "debugdata",
          "metricSavings": {
            "FCP": 90,
            "LCP": 170
          }
        },
        "overallSavingsBytes": 20883,
        "overallSavingsMs": 170,
        "type": "opportunity",
        "headings": [
          {
            "key": "url",
            "subItemsHeading": {
              "valueType": "code",
              "key": "source"
            },
            "valueType": "url",
            "label": "URL"
          },
          {
            "subItemsHeading": {
              "key": "sourceBytes"
            },
            "key": "totalBytes",
            "label": "Transfer Size",
            "valueType": "bytes"
          },
          {
            "key": "wastedBytes",
            "valueType": "bytes",
            "label": "Potential Savings",
            "subItemsHeading": {
              "key": "sourceWastedBytes"
            }
          }
        ],
        "sortedBy": [
          "wastedBytes"
        ]
      },
      "numericValue": 170,
      "numericUnit": "millisecond"
    },
    "dom-size": {
      "id": "dom-size",
      "title": "Avoids an excessive DOM size",
      "description": "A large DOM will increase memory usage, cause longer [style calculations](https://developers.google.com/web/fundamentals/performance/rendering/reduce-the-scope-and-complexity-of-style-calculations), and produce costly [layout reflows](https://developers.google.com/speed/articles/reflow). [Learn how to avoid an excessive DOM size](https://developer.chrome.com/docs/lighthouse/performance/dom-size/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "94 elements",
      "details": {
        "headings": [
          {
            "valueType": "text",
            "label": "Statistic",
            "key": "statistic"
          },
          {
            "key": "node",
            "valueType": "node",
            "label": "Element"
          },
          {
            "key": "value",
            "label": "Value",
            "valueType": "numeric"
          }
        ],
        "items": [
          {
            "value": {
              "value": 94,
              "type": "numeric",
              "granularity": 1
            },
            "statistic": "Total DOM Elements"
          },
          {
            "statistic": "Maximum DOM Depth",
            "value": {
              "granularity": 1,
              "type": "numeric",
              "value": 7
            },
            "node": {
              "type": "node",
              "boundingRect": {
                "right": 192,
                "height": 50,
                "width": 67,
                "bottom": 51,
                "top": 1,
                "left": 125
              },
              "nodeLabel": "Home",
              "path": "1,HTML,1,BODY,0,NAV,0,DIV,1,DIV,0,UL,0,LI,0,A",
              "lhId": "1-11-A",
              "snippet": "<a href=\"index.html\">",
              "selector": "div#myNavbar > ul.nav > li.active > a"
            }
          },
          {
            "statistic": "Maximum Child Elements",
            "node": {
              "selector": "body > main > section#contact > form#contact_form",
              "type": "node",
              "nodeLabel": "Name:\n\nEmail:\n\nInformation:\n\n",
              "snippet": "<form id=\"contact_form\" action=\"https://api.sheetmonkey.io/form/tuDJM67cMcUuvnVjVzPVXx\" method=\"POST\">",
              "boundingRect": {
                "height": 170,
                "left": 130,
                "bottom": 1787,
                "right": 850,
                "top": 1617,
                "width": 720
              },
              "lhId": "1-15-FORM",
              "path": "1,HTML,1,BODY,3,MAIN,5,SECTION,3,FORM"
            },
            "value": {
              "value": 13,
              "type": "numeric",
              "granularity": 1
            }
          }
        ],
        "type": "table"
      },
      "numericValue": 94,
      "numericUnit": "element"
    },
    "unminified-css": {
      "id": "unminified-css",
      "title": "Minify CSS",
      "description": "Minifying CSS files can reduce network payload sizes. [Learn how to minify CSS](https://developer.chrome.com/docs/lighthouse/performance/unminified-css/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "overallSavingsBytes": 0,
        "headings": [],
        "sortedBy": [
          "wastedBytes"
        ],
        "type": "opportunity",
        "overallSavingsMs": 0,
        "debugData": {
          "type": "debugdata",
          "metricSavings": {
            "FCP": 0,
            "LCP": 0
          }
        },
        "items": []
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "aria-input-field-name": {
      "id": "aria-input-field-name",
      "title": "ARIA input fields have accessible names",
      "description": "When an input field doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn more about input field labels](https://dequeuniversity.com/rules/axe/4.7/aria-input-field-name).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "label": {
      "id": "label",
      "title": "Form elements have associated labels",
      "description": "Labels ensure that form controls are announced properly by assistive technologies, like screen readers. [Learn more about form element labels](https://dequeuniversity.com/rules/axe/4.7/label).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "items": [],
        "headings": []
      }
    },
    "table-fake-caption": {
      "id": "table-fake-caption",
      "title": "Tables use `<caption>` instead of cells with the `[colspan]` attribute to indicate a caption.",
      "description": "Screen readers have features to make navigating tables easier. Ensuring that tables use the actual caption element instead of cells with the `[colspan]` attribute may improve the experience for screen reader users. [Learn more about captions](https://dequeuniversity.com/rules/axe/4.7/table-fake-caption).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "frame-title": {
      "id": "frame-title",
      "title": "`<frame>` or `<iframe>` elements have a title",
      "description": "Screen reader users rely on frame titles to describe the contents of frames. [Learn more about frame titles](https://dequeuniversity.com/rules/axe/4.7/frame-title).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "redirects": {
      "id": "redirects",
      "title": "Avoid multiple page redirects",
      "description": "Redirects introduce additional delays before the page can be loaded. [Learn how to avoid page redirects](https://developer.chrome.com/docs/lighthouse/performance/redirects/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "type": "opportunity",
        "overallSavingsMs": 0,
        "headings": [],
        "items": []
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "hreflang": {
      "id": "hreflang",
      "title": "Document has a valid `hreflang`",
      "description": "hreflang links tell search engines what version of a page they should list in search results for a given language or region. [Learn more about `hreflang`](https://developer.chrome.com/docs/lighthouse/seo/hreflang/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "items": [],
        "headings": []
      }
    },
    "non-composited-animations": {
      "id": "non-composited-animations",
      "title": "Avoid non-composited animations",
      "description": "Animations which are not composited can be janky and increase CLS. [Learn how to avoid non-composited animations](https://developer.chrome.com/docs/lighthouse/performance/non-composited-animations/)",
      "score": null,
      "scoreDisplayMode": "notApplicable",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "offscreen-content-hidden": {
      "id": "offscreen-content-hidden",
      "title": "Offscreen content is hidden from assistive technology",
      "description": "Offscreen content is hidden with display: none or aria-hidden=true. [Learn how to properly hide offscreen content](https://developer.chrome.com/docs/lighthouse/accessibility/offscreen-content-hidden/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "th-has-data-cells": {
      "id": "th-has-data-cells",
      "title": "`<th>` elements and elements with `[role=\"columnheader\"/\"rowheader\"]` have data cells they describe.",
      "description": "Screen readers have features to make navigating tables easier. Ensuring table headers always refer to some set of cells may improve the experience for screen reader users. [Learn more about table headers](https://dequeuniversity.com/rules/axe/4.7/th-has-data-cells).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "first-contentful-paint": {
      "id": "first-contentful-paint",
      "title": "First Contentful Paint",
      "description": "First Contentful Paint marks the time at which the first text or image is painted. [Learn more about the First Contentful Paint metric](https://developer.chrome.com/docs/lighthouse/performance/first-contentful-paint/).",
      "score": 0.84,
      "scoreDisplayMode": "numeric",
      "displayValue": "2.0 s",
      "numericValue": 1985.5,
      "numericUnit": "millisecond"
    },
    "html-xml-lang-mismatch": {
      "id": "html-xml-lang-mismatch",
      "title": "`<html>` element has an `[xml:lang]` attribute with the same base language as the `[lang]` attribute.",
      "description": "If the webpage does not specify a consistent language, then the screen reader might not announce the page's text correctly. [Learn more about the `lang` attribute](https://dequeuniversity.com/rules/axe/4.7/html-xml-lang-mismatch).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "diagnostics": {
      "id": "diagnostics",
      "title": "Diagnostics",
      "description": "Collection of useful page vitals.",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "type": "debugdata",
        "items": [
          {
            "numRequests": 9,
            "numTasksOver25ms": 0,
            "rtt": 0,
            "totalByteWeight": 1230328,
            "mainDocumentTransferSize": 3772,
            "numScripts": 2,
            "totalTaskTime": 87.51300000000006,
            "throughput": 205055094572.2441,
            "numStylesheets": 1,
            "numTasksOver50ms": 0,
            "numTasks": 127,
            "maxRtt": 15.5,
            "numTasksOver10ms": 3,
            "numTasksOver500ms": 0,
            "numTasksOver100ms": 0,
            "maxServerLatency": 39,
            "numFonts": 1
          }
        ]
      }
    },
    "uses-passive-event-listeners": {
      "id": "uses-passive-event-listeners",
      "title": "Uses passive listeners to improve scrolling performance",
      "description": "Consider marking your touch and wheel event listeners as `passive` to improve your page's scroll performance. [Learn more about adopting passive event listeners](https://developer.chrome.com/docs/lighthouse/best-practices/uses-passive-event-listeners/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "headings": [],
        "type": "table"
      }
    },
    "interactive": {
      "id": "interactive",
      "title": "Time to Interactive",
      "description": "Time to Interactive is the amount of time it takes for the page to become fully interactive. [Learn more about the Time to Interactive metric](https://developer.chrome.com/docs/lighthouse/performance/interactive/).",
      "score": 0.99,
      "scoreDisplayMode": "numeric",
      "displayValue": "2.0 s",
      "numericValue": 1985.5,
      "numericUnit": "millisecond"
    },
    "aria-valid-attr": {
      "id": "aria-valid-attr",
      "title": "`[aria-*]` attributes are valid and not misspelled",
      "description": "Assistive technologies, like screen readers, can't interpret ARIA attributes with invalid names. [Learn more about valid ARIA attributes](https://dequeuniversity.com/rules/axe/4.7/aria-valid-attr).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "label-content-name-mismatch": {
      "id": "label-content-name-mismatch",
      "title": "Elements with visible text labels have matching accessible names.",
      "description": "Visible text labels that do not match the accessible name can result in a confusing experience for screen reader users. [Learn more about accessible names](https://dequeuniversity.com/rules/axe/4.7/label-content-name-mismatch).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "tabindex": {
      "id": "tabindex",
      "title": "No element has a `[tabindex]` value greater than 0",
      "description": "A value greater than 0 implies an explicit navigation ordering. Although technically valid, this often creates frustrating experiences for users who rely on assistive technologies. [Learn more about the `tabindex` attribute](https://dequeuniversity.com/rules/axe/4.7/tabindex).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "image-alt": {
      "id": "image-alt",
      "title": "Image elements have `[alt]` attributes",
      "description": "Informative elements should aim for short, descriptive alternate text. Decorative elements can be ignored with an empty alt attribute. [Learn more about the `alt` attribute](https://dequeuniversity.com/rules/axe/4.7/image-alt).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "headings": [],
        "type": "table"
      }
    },
    "meta-refresh": {
      "id": "meta-refresh",
      "title": "The document does not use `<meta http-equiv=\"refresh\">`",
      "description": "Users do not expect a page to refresh automatically, and doing so will move focus back to the top of the page. This may create a frustrating or confusing experience. [Learn more about the refresh meta tag](https://dequeuniversity.com/rules/axe/4.7/meta-refresh).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "themed-omnibox": {
      "id": "themed-omnibox",
      "title": "Does not set a theme color for the address bar.",
      "description": "The browser address bar can be themed to match your site. [Learn more about theming the address bar](https://developer.chrome.com/docs/lighthouse/pwa/themed-omnibox/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "explanation": "Failures: No manifest was fetched,\nNo `<meta name=\"theme-color\">` tag found.",
      "details": {
        "items": [
          {
            "parseFailureReason": "No manifest was fetched",
            "themeColor": null,
            "failures": [
              "No manifest was fetched",
              "No `<meta name=\"theme-color\">` tag found"
            ],
            "isParseFailure": true
          }
        ],
        "type": "debugdata"
      }
    },
    "aria-required-parent": {
      "id": "aria-required-parent",
      "title": "`[role]`s are contained by their required parent element",
      "description": "Some ARIA child roles must be contained by specific parent roles to properly perform their intended accessibility functions. [Learn more about ARIA roles and required parent element](https://dequeuniversity.com/rules/axe/4.7/aria-required-parent).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "network-rtt": {
      "id": "network-rtt",
      "title": "Network Round Trip Times",
      "description": "Network round trip times (RTT) have a large impact on performance. If the RTT to an origin is high, it's an indication that servers closer to the user could improve performance. [Learn more about the Round Trip Time](https://hpbn.co/primer-on-latency-and-bandwidth/).",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "20 ms",
      "details": {
        "type": "table",
        "sortedBy": [
          "rtt"
        ],
        "items": [
          {
            "origin": "https://jxbang94.github.io",
            "rtt": 15.5
          },
          {
            "origin": "https://maxcdn.bootstrapcdn.com",
            "rtt": 0
          },
          {
            "origin": "https://ajax.googleapis.com",
            "rtt": 0
          }
        ],
        "headings": [
          {
            "valueType": "text",
            "key": "origin",
            "label": "URL"
          },
          {
            "key": "rtt",
            "label": "Time Spent",
            "granularity": 1,
            "valueType": "ms"
          }
        ]
      },
      "numericValue": 15.5,
      "numericUnit": "millisecond"
    },
    "uses-rel-preconnect": {
      "id": "uses-rel-preconnect",
      "title": "Preconnect to required origins",
      "description": "Consider adding `preconnect` or `dns-prefetch` resource hints to establish early connections to important third-party origins. [Learn how to preconnect to required origins](https://developer.chrome.com/docs/lighthouse/performance/uses-rel-preconnect/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "type": "opportunity",
        "overallSavingsMs": 0,
        "sortedBy": [
          "wastedMs"
        ],
        "headings": [],
        "items": []
      },
      "warnings": [],
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "content-width": {
      "id": "content-width",
      "title": "Content is not sized correctly for the viewport",
      "description": "If the width of your app's content doesn't match the width of the viewport, your app might not be optimized for mobile screens. [Learn how to size content for the viewport](https://developer.chrome.com/docs/lighthouse/pwa/content-width/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "explanation": "The viewport size of 981px does not match the window size of 412px."
    },
    "aria-tooltip-name": {
      "id": "aria-tooltip-name",
      "title": "ARIA `tooltip` elements have accessible names",
      "description": "When a tooltip element doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn how to name `tooltip` elements](https://dequeuniversity.com/rules/axe/4.7/aria-tooltip-name).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "paste-preventing-inputs": {
      "id": "paste-preventing-inputs",
      "title": "Allows users to paste into input fields",
      "description": "Preventing input pasting is a bad practice for the UX, and weakens security by blocking password managers.[Learn more about user-friendly input fields](https://developer.chrome.com/docs/lighthouse/best-practices/paste-preventing-inputs/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "headings": [],
        "items": []
      }
    },
    "script-treemap-data": {
      "id": "script-treemap-data",
      "title": "Script Treemap Data",
      "description": "Used for treemap app",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "type": "treemap-data",
        "nodes": [
          {
            "resourceBytes": 87533,
            "unusedBytes": 58169,
            "name": "https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"
          },
          {
            "resourceBytes": 39680,
            "name": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js",
            "unusedBytes": 31154
          }
        ]
      }
    },
    "tap-targets": {
      "id": "tap-targets",
      "title": "Tap targets are not sized appropriately",
      "description": "Interactive elements like buttons and links should be large enough (48x48px), or have enough space around them, to be easy enough to tap without overlapping onto other elements. [Learn more about tap targets](https://developer.chrome.com/docs/lighthouse/seo/tap-targets/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "explanation": "Tap targets are too small because there's no viewport meta tag optimized for mobile screens"
    },
    "document-title": {
      "id": "document-title",
      "title": "Document has a `<title>` element",
      "description": "The title gives screen reader users an overview of the page, and search engine users rely on it heavily to determine if a page is relevant to their search. [Learn more about document titles](https://dequeuniversity.com/rules/axe/4.7/document-title).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "headings": [],
        "items": []
      }
    },
    "html-has-lang": {
      "id": "html-has-lang",
      "title": "`<html>` element has a `[lang]` attribute",
      "description": "If a page doesn't specify a `lang` attribute, a screen reader assumes that the page is in the default language that the user chose when setting up the screen reader. If the page isn't actually in the default language, then the screen reader might not announce the page's text correctly. [Learn more about the `lang` attribute](https://dequeuniversity.com/rules/axe/4.7/html-has-lang).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "items": [],
        "headings": []
      }
    },
    "modern-image-formats": {
      "id": "modern-image-formats",
      "title": "Serve images in next-gen formats",
      "description": "Image formats like WebP and AVIF often provide better compression than PNG or JPEG, which means faster downloads and less data consumption. [Learn more about modern image formats](https://developer.chrome.com/docs/lighthouse/performance/uses-webp-images/).",
      "score": 0.18,
      "scoreDisplayMode": "numeric",
      "displayValue": "Potential savings of 666 KiB",
      "details": {
        "type": "opportunity",
        "debugData": {
          "metricSavings": {
            "FCP": 0,
            "LCP": 3310
          },
          "type": "debugdata"
        },
        "items": [
          {
            "wastedWebpBytes": 345215,
            "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-2.jpg",
            "totalBytes": 473937,
            "node": {
              "lhId": "1-23-IMG",
              "nodeLabel": "Image",
              "snippet": "<img src=\"assets/img/carousel-2.jpg\" alt=\"Image\">",
              "type": "node",
              "selector": "div#myCarousel > div.carousel-inner > div.item > img",
              "boundingRect": {
                "height": 0,
                "top": 0,
                "left": 0,
                "bottom": 0,
                "width": 0,
                "right": 0
              },
              "path": "1,HTML,1,BODY,1,DIV,3,DIV,1,DIV,0,IMG"
            },
            "fromProtocol": true,
            "isCrossOrigin": false,
            "wastedBytes": 326884.7
          },
          {
            "wastedWebpBytes": 237215,
            "fromProtocol": true,
            "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-1.jpg",
            "isCrossOrigin": false,
            "totalBytes": 523057,
            "wastedBytes": 265389.95,
            "node": {
              "boundingRect": {
                "right": 980,
                "top": 52,
                "bottom": 652,
                "height": 600,
                "left": 0,
                "width": 980
              },
              "path": "1,HTML,1,BODY,1,DIV,3,DIV,0,DIV,0,IMG",
              "snippet": "<img src=\"assets/img/carousel-1.jpg\" alt=\"Image of keyboard, controllers, mouse, smartphone, and headphones on a des…\">",
              "type": "node",
              "nodeLabel": "Image of keyboard, controllers, mouse, smartphone, and headphones on a desk.",
              "lhId": "1-9-IMG",
              "selector": "div#myCarousel > div.carousel-inner > div.item > img"
            }
          },
          {
            "wastedWebpBytes": 61849,
            "node": {
              "boundingRect": {
                "top": 1127,
                "left": 130,
                "height": 147,
                "width": 220,
                "bottom": 1273,
                "right": 350
              },
              "lhId": "1-25-IMG",
              "snippet": "<img src=\"assets/img/support.jpg\" class=\"img-responsive\" style=\"width:100%\" height=\"400\" alt=\"image of a few people in a circle with hands.\">",
              "type": "node",
              "path": "1,HTML,1,BODY,3,MAIN,3,DIV,0,DIV,0,DIV,1,IMG",
              "nodeLabel": "image of a few people in a circle with hands.",
              "selector": "div.container > div.row > div.col-sm-4 > img.img-responsive"
            },
            "totalBytes": 93007,
            "wastedBytes": 59761.8,
            "url": "https://jxbang94.github.io/Website-main/assets/img/support.jpg",
            "fromProtocol": true,
            "isCrossOrigin": false
          },
          {
            "url": "https://jxbang94.github.io/Website-main/assets/img/late.jpg",
            "node": {
              "boundingRect": {
                "right": 600,
                "width": 220,
                "height": 165,
                "left": 380,
                "top": 713,
                "bottom": 878
              },
              "selector": "div.container > div.row > div.col-sm-4 > img.img-responsive",
              "snippet": "<img src=\"assets/img/late.jpg\" class=\"img-responsive\" style=\"width:100%\" height=\"400\" alt=\"drawing of boy playing video games on a couch\">",
              "type": "node",
              "lhId": "1-24-IMG",
              "nodeLabel": "drawing of boy playing video games on a couch",
              "path": "1,HTML,1,BODY,3,MAIN,0,DIV,0,DIV,2,DIV,0,IMG"
            },
            "isCrossOrigin": false,
            "wastedWebpBytes": 26297,
            "wastedBytes": 29435.95,
            "totalBytes": 49959,
            "fromProtocol": true
          }
        ],
        "overallSavingsBytes": 681472.4,
        "headings": [
          {
            "key": "node",
            "valueType": "node"
          },
          {
            "valueType": "url",
            "key": "url",
            "label": "URL"
          },
          {
            "valueType": "bytes",
            "key": "totalBytes",
            "label": "Resource Size"
          },
          {
            "key": "wastedBytes",
            "label": "Potential Savings",
            "valueType": "bytes"
          }
        ],
        "sortedBy": [
          "wastedBytes"
        ],
        "overallSavingsMs": 3310
      },
      "warnings": [],
      "numericValue": 3310,
      "numericUnit": "millisecond"
    },
    "empty-heading": {
      "id": "empty-heading",
      "title": "All heading elements contain content.",
      "description": "A heading with no content or inaccessible text prevent screen reader users from accessing information on the page's structure. [Learn more about headings](https://dequeuniversity.com/rules/axe/4.7/empty-heading).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "aria-required-attr": {
      "id": "aria-required-attr",
      "title": "`[role]`s have all required `[aria-*]` attributes",
      "description": "Some ARIA roles have required attributes that describe the state of the element to screen readers. [Learn more about roles and required attributes](https://dequeuniversity.com/rules/axe/4.7/aria-required-attr).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "type": "table",
        "headings": []
      }
    },
    "deprecations": {
      "id": "deprecations",
      "title": "Avoids deprecated APIs",
      "description": "Deprecated APIs will eventually be removed from the browser. [Learn more about deprecated APIs](https://developer.chrome.com/docs/lighthouse/best-practices/deprecations/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "type": "table",
        "headings": []
      }
    },
    "http-status-code": {
      "id": "http-status-code",
      "title": "Page has successful HTTP status code",
      "description": "Pages with unsuccessful HTTP status codes may not be indexed properly. [Learn more about HTTP status codes](https://developer.chrome.com/docs/lighthouse/seo/http-status-code/).",
      "score": 1,
      "scoreDisplayMode": "binary"
    },
    "bypass": {
      "id": "bypass",
      "title": "The page contains a heading, skip link, or landmark region",
      "description": "Adding ways to bypass repetitive content lets keyboard users navigate the page more efficiently. [Learn more about bypass blocks](https://dequeuniversity.com/rules/axe/4.7/bypass).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "identical-links-same-purpose": {
      "id": "identical-links-same-purpose",
      "title": "Identical links have the same purpose.",
      "description": "Links with the same destination should have the same description, to help users understand the link's purpose and decide whether to follow it. [Learn more about identical links](https://dequeuniversity.com/rules/axe/4.7/identical-links-same-purpose).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "meta-description": {
      "id": "meta-description",
      "title": "Document does not have a meta description",
      "description": "Meta descriptions may be included in search results to concisely summarize page content. [Learn more about the meta description](https://developer.chrome.com/docs/lighthouse/seo/meta-description/).",
      "score": 0,
      "scoreDisplayMode": "binary"
    },
    "prioritize-lcp-image": {
      "id": "prioritize-lcp-image",
      "title": "Preload Largest Contentful Paint image",
      "description": "If the LCP element is dynamically added to the page, you should preload the image in order to improve LCP. [Learn more about preloading LCP elements](https://web.dev/optimize-lcp/#optimize-when-the-resource-is-discovered).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "type": "opportunity",
        "items": [],
        "debugData": {
          "type": "debugdata",
          "initiatorPath": [
            {
              "initiatorType": "parser",
              "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-1.jpg"
            },
            {
              "initiatorType": "other",
              "url": "https://jxbang94.github.io/Website-main/"
            }
          ],
          "pathLength": 2
        },
        "sortedBy": [
          "wastedMs"
        ],
        "overallSavingsMs": 0,
        "headings": []
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "structured-data": {
      "id": "structured-data",
      "title": "Structured data is valid",
      "description": "Run the [Structured Data Testing Tool](https://search.google.com/structured-data/testing-tool/) and the [Structured Data Linter](http://linter.structured-data.org/) to validate structured data. [Learn more about Structured Data](https://developer.chrome.com/docs/lighthouse/seo/structured-data/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "aria-command-name": {
      "id": "aria-command-name",
      "title": "`button`, `link`, and `menuitem` elements have accessible names",
      "description": "When an element doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn how to make command elements more accessible](https://dequeuniversity.com/rules/axe/4.7/aria-command-name).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "pwa-cross-browser": {
      "id": "pwa-cross-browser",
      "title": "Site works cross-browser",
      "description": "To reach the most number of users, sites should work across every major browser. [Learn about cross-browser compatibility](https://developer.chrome.com/docs/lighthouse/pwa/pwa-cross-browser/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "form-field-multiple-labels": {
      "id": "form-field-multiple-labels",
      "title": "No form fields have multiple labels",
      "description": "Form fields with multiple labels can be confusingly announced by assistive technologies like screen readers which use either the first, the last, or all of the labels. [Learn how to use form labels](https://dequeuniversity.com/rules/axe/4.7/form-field-multiple-labels).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "network-server-latency": {
      "id": "network-server-latency",
      "title": "Server Backend Latencies",
      "description": "Server latencies can impact web performance. If the server latency of an origin is high, it's an indication the server is overloaded or has poor backend performance. [Learn more about server response time](https://hpbn.co/primer-on-web-performance/#analyzing-the-resource-waterfall).",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "40 ms",
      "details": {
        "type": "table",
        "items": [
          {
            "origin": "https://jxbang94.github.io",
            "serverResponseTime": 39
          },
          {
            "origin": "https://maxcdn.bootstrapcdn.com",
            "serverResponseTime": 9
          },
          {
            "serverResponseTime": 1,
            "origin": "https://ajax.googleapis.com"
          }
        ],
        "sortedBy": [
          "serverResponseTime"
        ],
        "headings": [
          {
            "key": "origin",
            "label": "URL",
            "valueType": "text"
          },
          {
            "key": "serverResponseTime",
            "label": "Time Spent",
            "valueType": "ms",
            "granularity": 1
          }
        ]
      },
      "numericValue": 39,
      "numericUnit": "millisecond"
    },
    "focusable-controls": {
      "id": "focusable-controls",
      "title": "Interactive controls are keyboard focusable",
      "description": "Custom interactive controls are keyboard focusable and display a focus indicator. [Learn how to make custom controls focusable](https://developer.chrome.com/docs/lighthouse/accessibility/focusable-controls/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "focus-traps": {
      "id": "focus-traps",
      "title": "User focus is not accidentally trapped in a region",
      "description": "A user can tab into and out of any control or region without accidentally trapping their focus. [Learn how to avoid focus traps](https://developer.chrome.com/docs/lighthouse/accessibility/focus-traps/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "bootup-time": {
      "id": "bootup-time",
      "title": "JavaScript execution time",
      "description": "Consider reducing the time spent parsing, compiling, and executing JS. You may find delivering smaller JS payloads helps with this. [Learn how to reduce Javascript execution time](https://developer.chrome.com/docs/lighthouse/performance/bootup-time/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "0.1 s",
      "details": {
        "type": "table",
        "headings": [
          {
            "label": "URL",
            "valueType": "url",
            "key": "url"
          },
          {
            "granularity": 1,
            "key": "total",
            "label": "Total CPU Time",
            "valueType": "ms"
          },
          {
            "label": "Script Evaluation",
            "key": "scripting",
            "valueType": "ms",
            "granularity": 1
          },
          {
            "granularity": 1,
            "key": "scriptParseCompile",
            "label": "Script Parse",
            "valueType": "ms"
          }
        ],
        "summary": {
          "wastedMs": 94.04000000000002
        },
        "sortedBy": [
          "total"
        ],
        "items": [
          {
            "scriptParseCompile": 4.5440000000000005,
            "scripting": 11.575999999999995,
            "total": 165.65999999999997,
            "url": "https://jxbang94.github.io/Website-main/"
          },
          {
            "scriptParseCompile": 5.116,
            "total": 77.59600000000002,
            "scripting": 67.26000000000002,
            "url": "https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"
          },
          {
            "scripting": 5.544,
            "scriptParseCompile": 0,
            "total": 72.65599999999996,
            "url": "Unattributable"
          }
        ]
      },
      "numericValue": 94.04000000000002,
      "numericUnit": "millisecond"
    },
    "heading-order": {
      "id": "heading-order",
      "title": "Heading elements appear in a sequentially-descending order",
      "description": "Properly ordered headings that do not skip levels convey the semantic structure of the page, making it easier to navigate and understand when using assistive technologies. [Learn more about heading order](https://dequeuniversity.com/rules/axe/4.7/heading-order).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "headings": [],
        "type": "table"
      }
    },
    "duplicated-javascript": {
      "id": "duplicated-javascript",
      "title": "Remove duplicate modules in JavaScript bundles",
      "description": "Remove large, duplicate JavaScript modules from bundles to reduce unnecessary bytes consumed by network activity. ",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "headings": [],
        "type": "opportunity",
        "overallSavingsMs": 0,
        "items": [],
        "debugData": {
          "type": "debugdata",
          "metricSavings": {
            "LCP": 0,
            "FCP": 0
          }
        },
        "overallSavingsBytes": 0,
        "sortedBy": [
          "wastedBytes"
        ]
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "pwa-each-page-has-url": {
      "id": "pwa-each-page-has-url",
      "title": "Each page has a URL",
      "description": "Ensure individual pages are deep linkable via URL and that URLs are unique for the purpose of shareability on social media. [Learn more about providing deep links](https://developer.chrome.com/docs/lighthouse/pwa/pwa-each-page-has-url/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "button-name": {
      "id": "button-name",
      "title": "Buttons have an accessible name",
      "description": "When a button doesn't have an accessible name, screen readers announce it as \"button\", making it unusable for users who rely on screen readers. [Learn how to make buttons more accessible](https://dequeuniversity.com/rules/axe/4.7/button-name).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "robots-txt": {
      "id": "robots-txt",
      "title": "robots.txt is valid",
      "description": "If your robots.txt file is malformed, crawlers may not be able to understand how you want your website to be crawled or indexed. [Learn more about robots.txt](https://developer.chrome.com/docs/lighthouse/seo/invalid-robots-txt/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "total-byte-weight": {
      "id": "total-byte-weight",
      "title": "Avoids enormous network payloads",
      "description": "Large network payloads cost users real money and are highly correlated with long load times. [Learn how to reduce payload sizes](https://developer.chrome.com/docs/lighthouse/performance/total-byte-weight/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "displayValue": "Total size was 1,201 KiB",
      "details": {
        "headings": [
          {
            "valueType": "url",
            "label": "URL",
            "key": "url"
          },
          {
            "valueType": "bytes",
            "key": "totalBytes",
            "label": "Transfer Size"
          }
        ],
        "items": [
          {
            "totalBytes": 523774,
            "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-1.jpg"
          },
          {
            "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-2.jpg",
            "totalBytes": 474633
          },
          {
            "totalBytes": 93723,
            "url": "https://jxbang94.github.io/Website-main/assets/img/support.jpg"
          },
          {
            "url": "https://jxbang94.github.io/Website-main/assets/img/late.jpg",
            "totalBytes": 50653
          },
          {
            "url": "https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js",
            "totalBytes": 31425
          },
          {
            "totalBytes": 21238,
            "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css"
          },
          {
            "totalBytes": 18925,
            "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/fonts/glyphicons-halflings-regular.woff2"
          },
          {
            "totalBytes": 12185,
            "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"
          },
          {
            "url": "https://jxbang94.github.io/Website-main/",
            "totalBytes": 3772
          }
        ],
        "type": "table",
        "sortedBy": [
          "totalBytes"
        ]
      },
      "numericValue": 1230328,
      "numericUnit": "byte"
    },
    "layout-shift-elements": {
      "id": "layout-shift-elements",
      "title": "Avoid large layout shifts",
      "description": "These DOM elements contribute most to the CLS of the page. [Learn how to improve CLS](https://web.dev/optimize-cls/)",
      "score": null,
      "scoreDisplayMode": "informative",
      "displayValue": "5 elements found",
      "details": {
        "items": [
          {
            "node": {
              "boundingRect": {
                "bottom": 1807,
                "top": 693,
                "width": 980,
                "right": 980,
                "height": 1114,
                "left": 0
              },
              "selector": "body > main",
              "nodeLabel": "\n\n\nWhat is Gaming Addiction\n\nAccording to Cleveland Clinic, \"Video game addicti…",
              "path": "1,HTML,1,BODY,3,MAIN",
              "snippet": "<main>",
              "type": "node",
              "lhId": "page-1-MAIN"
            },
            "score": 0.24462929597099545
          },
          {
            "node": {
              "type": "node",
              "selector": "body > footer.container-fluid",
              "snippet": "<footer class=\"container-fluid text-center\">",
              "path": "1,HTML,1,BODY,4,FOOTER",
              "boundingRect": {
                "top": 1807,
                "width": 980,
                "bottom": 1887,
                "left": 0,
                "height": 80,
                "right": 980
              },
              "lhId": "page-2-FOOTER",
              "nodeLabel": "© 2023 Level Down"
            },
            "score": 0.022835873602893388
          },
          {
            "score": 0.01164629553747563,
            "node": {
              "type": "node",
              "boundingRect": {
                "right": 784,
                "top": 496,
                "height": 136,
                "width": 588,
                "left": 196,
                "bottom": 632
              },
              "nodeLabel": "Community Help\n\nFind a group that wants to help you",
              "selector": "div#myCarousel > div.carousel-inner > div.item > div.carousel-caption",
              "snippet": "<div class=\"carousel-caption\">",
              "path": "1,HTML,1,BODY,1,DIV,3,DIV,0,DIV,1,DIV",
              "lhId": "page-3-DIV"
            }
          },
          {
            "score": 0.004335667757294436,
            "node": {
              "selector": "main > div.container > div.row > p",
              "type": "node",
              "lhId": "page-4-P",
              "path": "1,HTML,1,BODY,3,MAIN,0,DIV,0,DIV,5,P",
              "snippet": "<p>",
              "boundingRect": {
                "height": 120,
                "bottom": 936,
                "left": 115,
                "top": 816,
                "right": 865,
                "width": 750
              },
              "nodeLabel": "People are frequently drawn into gaming by the gratification of progress and th…"
            }
          },
          {
            "node": {
              "boundingRect": {
                "left": 115,
                "width": 750,
                "top": 816,
                "height": 120,
                "bottom": 936,
                "right": 865
              },
              "type": "node",
              "selector": "main > div.container > div.row > p",
              "snippet": "<p>",
              "lhId": "page-4-P",
              "path": "1,HTML,1,BODY,3,MAIN,0,DIV,0,DIV,5,P",
              "nodeLabel": "People are frequently drawn into gaming by the gratification of progress and th…"
            },
            "score": 0.004217690403354451
          }
        ],
        "headings": [
          {
            "label": "Element",
            "valueType": "node",
            "key": "node"
          },
          {
            "label": "CLS Contribution",
            "valueType": "numeric",
            "granularity": 0.001,
            "key": "score"
          }
        ],
        "type": "table"
      }
    },
    "unminified-javascript": {
      "id": "unminified-javascript",
      "title": "Minify JavaScript",
      "description": "Minifying JavaScript files can reduce payload sizes and script parse time. [Learn how to minify JavaScript](https://developer.chrome.com/docs/lighthouse/performance/unminified-javascript/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "overallSavingsMs": 0,
        "debugData": {
          "metricSavings": {
            "FCP": 0,
            "LCP": 0
          },
          "type": "debugdata"
        },
        "items": [],
        "type": "opportunity",
        "overallSavingsBytes": 0,
        "headings": [],
        "sortedBy": [
          "wastedBytes"
        ]
      },
      "warnings": [],
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "uses-rel-preload": {
      "id": "uses-rel-preload",
      "title": "Preload key requests",
      "description": "Consider using `<link rel=preload>` to prioritize fetching resources that are currently requested later in page load. [Learn how to preload key requests](https://developer.chrome.com/docs/lighthouse/performance/uses-rel-preload/).",
      "score": null,
      "scoreDisplayMode": "notApplicable",
      "details": {
        "items": [],
        "overallSavingsMs": 0,
        "headings": [],
        "type": "opportunity"
      }
    },
    "link-in-text-block": {
      "id": "link-in-text-block",
      "title": "Links are distinguishable without relying on color.",
      "description": "Low-contrast text is difficult or impossible for many users to read. Link text that is discernible improves the experience for users with low vision. [Learn how to make links distinguishable](https://dequeuniversity.com/rules/axe/4.7/link-in-text-block).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "no-document-write": {
      "id": "no-document-write",
      "title": "Avoids `document.write()`",
      "description": "For users on slow connections, external scripts dynamically injected via `document.write()` can delay page load by tens of seconds. [Learn how to avoid document.write()](https://developer.chrome.com/docs/lighthouse/best-practices/no-document-write/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "items": [],
        "headings": []
      }
    },
    "visual-order-follows-dom": {
      "id": "visual-order-follows-dom",
      "title": "Visual order on the page follows DOM order",
      "description": "DOM order matches the visual order, improving navigation for assistive technology. [Learn more about DOM and visual ordering](https://developer.chrome.com/docs/lighthouse/accessibility/visual-order-follows-dom/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "aria-toggle-field-name": {
      "id": "aria-toggle-field-name",
      "title": "ARIA toggle fields have accessible names",
      "description": "When a toggle field doesn't have an accessible name, screen readers announce it with a generic name, making it unusable for users who rely on screen readers. [Learn more about toggle fields](https://dequeuniversity.com/rules/axe/4.7/aria-toggle-field-name).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "input-image-alt": {
      "id": "input-image-alt",
      "title": "`<input type=\"image\">` elements have `[alt]` text",
      "description": "When an image is being used as an `<input>` button, providing alternative text can help screen reader users understand the purpose of the button. [Learn about input image alt text](https://dequeuniversity.com/rules/axe/4.7/input-image-alt).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "maskable-icon": {
      "id": "maskable-icon",
      "title": "Manifest doesn't have a maskable icon",
      "description": "A maskable icon ensures that the image fills the entire shape without being letterboxed when installing the app on a device. [Learn about maskable manifest icons](https://developer.chrome.com/docs/lighthouse/pwa/maskable-icon-audit/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "explanation": "No manifest was fetched"
    },
    "installable-manifest": {
      "id": "installable-manifest",
      "title": "Web app manifest or service worker do not meet the installability requirements",
      "description": "Service worker is the technology that enables your app to use many Progressive Web App features, such as offline, add to homescreen, and push notifications. With proper service worker and manifest implementations, browsers can proactively prompt users to add your app to their homescreen, which can lead to higher engagement. [Learn more about manifest installability requirements](https://developer.chrome.com/docs/lighthouse/pwa/installable-manifest/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "displayValue": "1 reason",
      "details": {
        "type": "table",
        "headings": [
          {
            "valueType": "text",
            "key": "reason",
            "label": "Failure reason"
          }
        ],
        "debugData": {
          "manifestUrl": null,
          "type": "debugdata"
        },
        "items": [
          {
            "reason": "No manifest was fetched"
          }
        ]
      },
      "warnings": [],
      "numericValue": 1,
      "numericUnit": "element"
    },
    "managed-focus": {
      "id": "managed-focus",
      "title": "The user's focus is directed to new content added to the page",
      "description": "If new content, such as a dialog, is added to the page, the user's focus is directed to it. [Learn how to direct focus to new content](https://developer.chrome.com/docs/lighthouse/accessibility/managed-focus/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "aria-required-children": {
      "id": "aria-required-children",
      "title": "Elements with an ARIA `[role]` that require children to contain a specific `[role]` have all required children.",
      "description": "Some ARIA parent roles must contain specific child roles to perform their intended accessibility functions. [Learn more about roles and required children elements](https://dequeuniversity.com/rules/axe/4.7/aria-required-children).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "unused-css-rules": {
      "id": "unused-css-rules",
      "title": "Reduce unused CSS",
      "description": "Reduce unused rules from stylesheets and defer CSS not used for above-the-fold content to decrease bytes consumed by network activity. [Learn how to reduce unused CSS](https://developer.chrome.com/docs/lighthouse/performance/unused-css-rules/).",
      "score": 0.88,
      "scoreDisplayMode": "numeric",
      "displayValue": "Potential savings of 19 KiB",
      "details": {
        "sortedBy": [
          "wastedBytes"
        ],
        "type": "opportunity",
        "overallSavingsBytes": 19358,
        "headings": [
          {
            "valueType": "url",
            "label": "URL",
            "key": "url"
          },
          {
            "key": "totalBytes",
            "valueType": "bytes",
            "label": "Transfer Size"
          },
          {
            "key": "wastedBytes",
            "valueType": "bytes",
            "label": "Potential Savings"
          }
        ],
        "debugData": {
          "type": "debugdata",
          "metricSavings": {
            "LCP": 170,
            "FCP": 0
          }
        },
        "items": [
          {
            "wastedBytes": 19358,
            "wastedPercent": 91.14583762154508,
            "totalBytes": 21238,
            "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css"
          }
        ],
        "overallSavingsMs": 170
      },
      "numericValue": 170,
      "numericUnit": "millisecond"
    },
    "aria-valid-attr-value": {
      "id": "aria-valid-attr-value",
      "title": "`[aria-*]` attributes have valid values",
      "description": "Assistive technologies, like screen readers, can't interpret ARIA attributes with invalid values. [Learn more about valid values for ARIA attributes](https://dequeuniversity.com/rules/axe/4.7/aria-valid-attr-value).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "dlitem": {
      "id": "dlitem",
      "title": "Definition list items are wrapped in `<dl>` elements",
      "description": "Definition list items (`<dt>` and `<dd>`) must be wrapped in a parent `<dl>` element to ensure that screen readers can properly announce them. [Learn how to structure definition lists correctly](https://dequeuniversity.com/rules/axe/4.7/dlitem).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "link-text": {
      "id": "link-text",
      "title": "Links have descriptive text",
      "description": "Descriptive link text helps search engines understand your content. [Learn how to make links more accessible](https://developer.chrome.com/docs/lighthouse/seo/link-text/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "type": "table",
        "items": []
      }
    },
    "listitem": {
      "id": "listitem",
      "title": "List items (`<li>`) are contained within `<ul>`, `<ol>` or `<menu>` parent elements",
      "description": "Screen readers require list items (`<li>`) to be contained within a parent `<ul>`, `<ol>` or `<menu>` to be announced properly. [Learn more about proper list structure](https://dequeuniversity.com/rules/axe/4.7/listitem).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "pwa-page-transitions": {
      "id": "pwa-page-transitions",
      "title": "Page transitions don't feel like they block on the network",
      "description": "Transitions should feel snappy as you tap around, even on a slow network. This experience is key to a user's perception of performance. [Learn more about page transitions](https://developer.chrome.com/docs/lighthouse/pwa/pwa-page-transitions/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "inspector-issues": {
      "id": "inspector-issues",
      "title": "No issues in the `Issues` panel in Chrome Devtools",
      "description": "Issues logged to the `Issues` panel in Chrome Devtools indicate unresolved problems. They can come from network request failures, insufficient security controls, and other browser concerns. Open up the Issues panel in Chrome DevTools for more details on each issue.",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "headings": [],
        "items": []
      }
    },
    "performance-budget": {
      "id": "performance-budget",
      "title": "Performance budget",
      "description": "Keep the quantity and size of network requests under the targets set by the provided performance budget. [Learn more about performance budgets](https://developers.google.com/web/tools/lighthouse/audits/budgets).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "meta-viewport": {
      "id": "meta-viewport",
      "title": "`[user-scalable=\"no\"]` is not used in the `<meta name=\"viewport\">` element and the `[maximum-scale]` attribute is not less than 5.",
      "description": "Disabling zooming is problematic for users with low vision who rely on screen magnification to properly see the contents of a web page. [Learn more about the viewport meta tag](https://dequeuniversity.com/rules/axe/4.7/meta-viewport).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "preload-fonts": {
      "id": "preload-fonts",
      "title": "Fonts with `font-display: optional` are preloaded",
      "description": "Preload `optional` fonts so first-time visitors may use them. [Learn more about preloading fonts](https://web.dev/preload-optional-fonts/)",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "charset": {
      "id": "charset",
      "title": "Properly defines charset",
      "description": "A character encoding declaration is required. It can be done with a `<meta>` tag in the first 1024 bytes of the HTML or in the Content-Type HTTP response header. [Learn more about declaring the character encoding](https://developer.chrome.com/docs/lighthouse/best-practices/charset/).",
      "score": 1,
      "scoreDisplayMode": "binary"
    },
    "custom-controls-roles": {
      "id": "custom-controls-roles",
      "title": "Custom controls have ARIA roles",
      "description": "Custom interactive controls have appropriate ARIA roles. [Learn how to add roles to custom controls](https://developer.chrome.com/docs/lighthouse/accessibility/custom-control-roles/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "uses-responsive-images": {
      "id": "uses-responsive-images",
      "title": "Properly size images",
      "description": "Serve images that are appropriately-sized to save cellular data and improve load time. [Learn how to size images](https://developer.chrome.com/docs/lighthouse/performance/uses-responsive-images/).",
      "score": 0.32,
      "scoreDisplayMode": "numeric",
      "displayValue": "Potential savings of 361 KiB",
      "details": {
        "headings": [
          {
            "key": "node",
            "valueType": "node"
          },
          {
            "key": "url",
            "valueType": "url",
            "label": "URL"
          },
          {
            "label": "Resource Size",
            "key": "totalBytes",
            "valueType": "bytes"
          },
          {
            "key": "wastedBytes",
            "valueType": "bytes",
            "label": "Potential Savings"
          }
        ],
        "sortedBy": [
          "wastedBytes"
        ],
        "items": [
          {
            "node": {
              "lhId": "1-9-IMG",
              "snippet": "<img src=\"assets/img/carousel-1.jpg\" alt=\"Image of keyboard, controllers, mouse, smartphone, and headphones on a des…\">",
              "type": "node",
              "path": "1,HTML,1,BODY,1,DIV,3,DIV,0,DIV,0,IMG",
              "nodeLabel": "Image of keyboard, controllers, mouse, smartphone, and headphones on a desk.",
              "selector": "div#myCarousel > div.carousel-inner > div.item > img",
              "boundingRect": {
                "bottom": 652,
                "left": 0,
                "width": 980,
                "top": 52,
                "right": 980,
                "height": 600
              }
            },
            "url": "https://jxbang94.github.io/Website-main/assets/img/carousel-1.jpg",
            "wastedBytes": 277772,
            "wastedPercent": 53.10546874999999,
            "totalBytes": 523057
          },
          {
            "wastedPercent": 81.65902777777778,
            "wastedBytes": 75949,
            "node": {
              "path": "1,HTML,1,BODY,3,MAIN,3,DIV,0,DIV,0,DIV,1,IMG",
              "type": "node",
              "snippet": "<img src=\"assets/img/support.jpg\" class=\"img-responsive\" style=\"width:100%\" height=\"400\" alt=\"image of a few people in a circle with hands.\">",
              "selector": "div.container > div.row > div.col-sm-4 > img.img-responsive",
              "lhId": "1-25-IMG",
              "nodeLabel": "image of a few people in a circle with hands.",
              "boundingRect": {
                "bottom": 1273,
                "height": 147,
                "top": 1127,
                "width": 220,
                "right": 350,
                "left": 130
              }
            },
            "totalBytes": 93007,
            "url": "https://jxbang94.github.io/Website-main/assets/img/support.jpg"
          },
          {
            "totalBytes": 49959,
            "wastedBytes": 15638,
            "url": "https://jxbang94.github.io/Website-main/assets/img/late.jpg",
            "node": {
              "nodeLabel": "drawing of boy playing video games on a couch",
              "selector": "div.container > div.row > div.col-sm-4 > img.img-responsive",
              "path": "1,HTML,1,BODY,3,MAIN,0,DIV,0,DIV,2,DIV,0,IMG",
              "type": "node",
              "boundingRect": {
                "bottom": 878,
                "width": 220,
                "right": 600,
                "top": 713,
                "left": 380,
                "height": 165
              },
              "snippet": "<img src=\"assets/img/late.jpg\" class=\"img-responsive\" style=\"width:100%\" height=\"400\" alt=\"drawing of boy playing video games on a couch\">",
              "lhId": "1-24-IMG"
            },
            "wastedPercent": 31.30098257322952
          }
        ],
        "overallSavingsMs": 1820,
        "debugData": {
          "type": "debugdata",
          "metricSavings": {
            "LCP": 1820,
            "FCP": 0
          }
        },
        "overallSavingsBytes": 369359,
        "type": "opportunity"
      },
      "numericValue": 1820,
      "numericUnit": "millisecond"
    },
    "valid-source-maps": {
      "id": "valid-source-maps",
      "title": "Page has valid source maps",
      "description": "Source maps translate minified code to the original source code. This helps developers debug in production. In addition, Lighthouse is able to provide further insights. Consider deploying source maps to take advantage of these benefits. [Learn more about source maps](https://developer.chrome.com/docs/devtools/javascript/source-maps/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "efficient-animated-content": {
      "id": "efficient-animated-content",
      "title": "Use video formats for animated content",
      "description": "Large GIFs are inefficient for delivering animated content. Consider using MPEG4/WebM videos for animations and PNG/WebP for static images instead of GIF to save network bytes. [Learn more about efficient video formats](https://developer.chrome.com/docs/lighthouse/performance/efficient-animated-content/)",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "sortedBy": [
          "wastedBytes"
        ],
        "headings": [],
        "type": "opportunity",
        "overallSavingsBytes": 0,
        "items": [],
        "overallSavingsMs": 0,
        "debugData": {
          "type": "debugdata",
          "metricSavings": {
            "FCP": 0,
            "LCP": 0
          }
        }
      },
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "screenshot-thumbnails": {
      "id": "screenshot-thumbnails",
      "title": "Screenshot Thumbnails",
      "description": "This is what the load of your site looked like.",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "items": [
          {
            "timing": 375,
            "data": "data:image/jpeg;base64,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",
            "timestamp": 3872843084523
          },
          {
            "timing": 750,
            "data": "data:image/jpeg;base64,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",
            "timestamp": 3872843459523
          },
          {
            "timestamp": 3872843834523,
            "timing": 1125,
            "data": "data:image/jpeg;base64,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"
          },
          {
            "timestamp": 3872844209523,
            "timing": 1500,
            "data": "data:image/jpeg;base64,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"
          },
          {
            "data": "data:image/jpeg;base64,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",
            "timestamp": 3872844584523,
            "timing": 1875
          },
          {
            "timing": 2250,
            "timestamp": 3872844959523,
            "data": "data:image/jpeg;base64,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"
          },
          {
            "timestamp": 3872845334523,
            "timing": 2625,
            "data": "data:image/jpeg;base64,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"
          },
          {
            "data": "data:image/jpeg;base64,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",
            "timing": 3000,
            "timestamp": 3872845709523
          }
        ],
        "type": "filmstrip",
        "scale": 3000
      }
    },
    "is-on-https": {
      "id": "is-on-https",
      "title": "Uses HTTPS",
      "description": "All sites should be protected with HTTPS, even ones that don't handle sensitive data. This includes avoiding [mixed content](https://developers.google.com/web/fundamentals/security/prevent-mixed-content/what-is-mixed-content), where some resources are loaded over HTTP despite the initial request being served over HTTPS. HTTPS prevents intruders from tampering with or passively listening in on the communications between your app and your users, and is a prerequisite for HTTP/2 and many new web platform APIs. [Learn more about HTTPS](https://developer.chrome.com/docs/lighthouse/pwa/is-on-https/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "items": [],
        "type": "table"
      }
    },
    "timing-budget": {
      "id": "timing-budget",
      "title": "Timing budget",
      "description": "Set a timing budget to help you keep an eye on the performance of your site. Performant sites load fast and respond to user input events quickly. [Learn more about performance budgets](https://developers.google.com/web/tools/lighthouse/audits/budgets).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "metrics": {
      "id": "metrics",
      "title": "Metrics",
      "description": "Collects all available metrics.",
      "score": null,
      "scoreDisplayMode": "informative",
      "details": {
        "type": "debugdata",
        "items": [
          {
            "observedFirstVisualChangeTs": 3872842862523,
            "timeToFirstByte": 639,
            "observedFirstContentfulPaintAllFramesTs": 3872842863919,
            "observedTraceEnd": 2569,
            "speedIndex": 1986,
            "cumulativeLayoutShiftMainFrame": 0.2944306790816325,
            "observedSpeedIndexTs": 3872842941252,
            "observedCumulativeLayoutShift": 0.2944306790816325,
            "observedDomContentLoaded": 145,
            "largestContentfulPaint": 7621,
            "observedNavigationStart": 0,
            "observedFirstContentfulPaintTs": 3872842863919,
            "firstMeaningfulPaint": 1986,
            "lcpLoadEnd": 6812,
            "observedDomContentLoadedTs": 3872842854688,
            "observedTimeOrigin": 0,
            "observedFirstContentfulPaint": 154,
            "observedLargestContentfulPaintTs": 3872842976108,
            "observedFirstMeaningfulPaintTs": 3872842863919,
            "observedSpeedIndex": 232,
            "observedFirstPaintTs": 3872842863919,
            "interactive": 1986,
            "observedNavigationStartTs": 3872842709523,
            "totalBlockingTime": 0,
            "maxPotentialFID": 50,
            "observedFirstVisualChange": 153,
            "observedTraceEndTs": 3872845278678,
            "observedLastVisualChange": 270,
            "observedLargestContentfulPaintAllFrames": 267,
            "observedTimeOriginTs": 3872842709523,
            "lcpLoadStart": 2387,
            "observedCumulativeLayoutShiftMainFrame": 0.2944306790816325,
            "cumulativeLayoutShift": 0.2944306790816325,
            "observedFirstMeaningfulPaint": 154,
            "observedLoad": 249,
            "observedLargestContentfulPaintAllFramesTs": 3872842976108,
            "observedFirstContentfulPaintAllFrames": 154,
            "observedFirstPaint": 154,
            "observedLoadTs": 3872842958727,
            "observedLastVisualChangeTs": 3872842979523,
            "firstContentfulPaint": 1986,
            "observedLargestContentfulPaint": 267
          },
          {
            "lcpInvalidated": false
          }
        ]
      },
      "numericValue": 1986,
      "numericUnit": "millisecond"
    },
    "input-button-name": {
      "id": "input-button-name",
      "title": "Input buttons have discernible text.",
      "description": "Adding discernable and accessible text to input buttons may help screen reader users understand the purpose of the input button. [Learn more about input buttons](https://dequeuniversity.com/rules/axe/4.7/input-button-name).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [],
        "headings": [],
        "type": "table"
      }
    },
    "aria-hidden-focus": {
      "id": "aria-hidden-focus",
      "title": "`[aria-hidden=\"true\"]` elements do not contain focusable descendents",
      "description": "Focusable descendents within an `[aria-hidden=\"true\"]` element prevent those interactive elements from being available to users of assistive technologies like screen readers. [Learn how `aria-hidden` affects focusable elements](https://dequeuniversity.com/rules/axe/4.7/aria-hidden-focus).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "headings": [],
        "type": "table",
        "items": []
      }
    },
    "offscreen-images": {
      "id": "offscreen-images",
      "title": "Defer offscreen images",
      "description": "Consider lazy-loading offscreen and hidden images after all critical resources have finished loading to lower time to interactive. [Learn how to defer offscreen images](https://developer.chrome.com/docs/lighthouse/performance/offscreen-images/).",
      "score": 1,
      "scoreDisplayMode": "numeric",
      "details": {
        "overallSavingsBytes": 0,
        "sortedBy": [
          "wastedBytes"
        ],
        "headings": [],
        "overallSavingsMs": 0,
        "items": [],
        "debugData": {
          "type": "debugdata",
          "metricSavings": {
            "FCP": 0,
            "LCP": 0
          }
        },
        "type": "opportunity"
      },
      "warnings": [],
      "numericValue": 0,
      "numericUnit": "millisecond"
    },
    "valid-lang": {
      "id": "valid-lang",
      "title": "`[lang]` attributes have a valid value",
      "description": "Specifying a valid [BCP 47 language](https://www.w3.org/International/questions/qa-choosing-language-tags#question) on elements helps ensure that text is pronounced correctly by a screen reader. [Learn how to use the `lang` attribute](https://dequeuniversity.com/rules/axe/4.7/valid-lang).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    },
    "font-display": {
      "id": "font-display",
      "title": "Ensure text remains visible during webfont load",
      "description": "Leverage the `font-display` CSS feature to ensure text is user-visible while webfonts are loading. [Learn more about `font-display`](https://developer.chrome.com/docs/lighthouse/performance/font-display/).",
      "score": 0,
      "scoreDisplayMode": "binary",
      "details": {
        "items": [
          {
            "url": "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/fonts/glyphicons-halflings-regular.woff2",
            "wastedMs": 68.49500036239624
          }
        ],
        "headings": [
          {
            "label": "URL",
            "valueType": "url",
            "key": "url"
          },
          {
            "label": "Potential Savings",
            "key": "wastedMs",
            "valueType": "ms"
          }
        ],
        "type": "table"
      },
      "warnings": []
    },
    "interactive-element-affordance": {
      "id": "interactive-element-affordance",
      "title": "Interactive elements indicate their purpose and state",
      "description": "Interactive elements, such as links and buttons, should indicate their state and be distinguishable from non-interactive elements. [Learn how to decorate interactive elements with affordance hints](https://developer.chrome.com/docs/lighthouse/accessibility/interactive-element-affordance/).",
      "score": null,
      "scoreDisplayMode": "manual"
    },
    "errors-in-console": {
      "id": "errors-in-console",
      "title": "No browser errors logged to the console",
      "description": "Errors logged to the console indicate unresolved problems. They can come from network request failures and other browser concerns. [Learn more about this errors in console diagnostic audit](https://developer.chrome.com/docs/lighthouse/best-practices/errors-in-console/)",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
        "type": "table",
        "items": [],
        "headings": []
      }
    },
    "canonical": {
      "id": "canonical",
      "title": "Document has a valid `rel=canonical`",
      "description": "Canonical links suggest which URL to show in search results. [Learn more about canonical links](https://developer.chrome.com/docs/lighthouse/seo/canonical/).",
      "score": null,
      "scoreDisplayMode": "notApplicable"
    }
  },
  "categories": {
    "performance": {
      "id": "performance",
      "title": "Performance",
      "score": 0.59,
      "auditRefs": [
        {
          "id": "first-contentful-paint",
          "weight": 10,
          "group": "metrics",
          "acronym": "FCP",
          "relevantAudits": [
            "server-response-time",
            "render-blocking-resources",
            "redirects",
            "critical-request-chains",
            "uses-text-compression",
            "uses-rel-preconnect",
            "uses-rel-preload",
            "font-display",
            "unminified-javascript",
            "unminified-css",
            "unused-css-rules"
          ]
        },
        {
          "id": "largest-contentful-paint",
          "weight": 25,
          "group": "metrics",
          "acronym": "LCP",
          "relevantAudits": [
            "server-response-time",
            "render-blocking-resources",
            "redirects",
            "critical-request-chains",
            "uses-text-compression",
            "uses-rel-preconnect",
            "uses-rel-preload",
            "font-display",
            "unminified-javascript",
            "unminified-css",
            "unused-css-rules",
            "largest-contentful-paint-element",
            "prioritize-lcp-image",
            "unused-javascript",
            "efficient-animated-content",
            "total-byte-weight",
            "lcp-lazy-loaded"
          ]
        },
        {
          "id": "total-blocking-time",
          "weight": 30,
          "group": "metrics",
          "acronym": "TBT",
          "relevantAudits": [
            "long-tasks",
            "third-party-summary",
            "third-party-facades",
            "bootup-time",
            "mainthread-work-breakdown",
            "dom-size",
            "duplicated-javascript",
            "legacy-javascript",
            "viewport"
          ]
        },
        {
          "id": "cumulative-layout-shift",
          "weight": 25,
          "group": "metrics",
          "acronym": "CLS",
          "relevantAudits": [
            "layout-shift-elements",
            "non-composited-animations",
            "unsized-images"
          ]
        },
        {
          "id": "speed-index",
          "weight": 10,
          "group": "metrics",
          "acronym": "SI"
        },
        {
          "id": "interactive",
          "weight": 0,
          "group": "hidden",
          "acronym": "TTI"
        },
        {
          "id": "max-potential-fid",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "first-meaningful-paint",
          "weight": 0,
          "group": "hidden",
          "acronym": "FMP"
        },
        {
          "id": "render-blocking-resources",
          "weight": 0
        },
        {
          "id": "uses-responsive-images",
          "weight": 0
        },
        {
          "id": "offscreen-images",
          "weight": 0
        },
        {
          "id": "unminified-css",
          "weight": 0
        },
        {
          "id": "unminified-javascript",
          "weight": 0
        },
        {
          "id": "unused-css-rules",
          "weight": 0
        },
        {
          "id": "unused-javascript",
          "weight": 0
        },
        {
          "id": "uses-optimized-images",
          "weight": 0
        },
        {
          "id": "modern-image-formats",
          "weight": 0
        },
        {
          "id": "uses-text-compression",
          "weight": 0
        },
        {
          "id": "uses-rel-preconnect",
          "weight": 0
        },
        {
          "id": "server-response-time",
          "weight": 0
        },
        {
          "id": "redirects",
          "weight": 0
        },
        {
          "id": "uses-rel-preload",
          "weight": 0
        },
        {
          "id": "efficient-animated-content",
          "weight": 0
        },
        {
          "id": "duplicated-javascript",
          "weight": 0
        },
        {
          "id": "legacy-javascript",
          "weight": 0
        },
        {
          "id": "prioritize-lcp-image",
          "weight": 0
        },
        {
          "id": "total-byte-weight",
          "weight": 0
        },
        {
          "id": "uses-long-cache-ttl",
          "weight": 0
        },
        {
          "id": "dom-size",
          "weight": 0
        },
        {
          "id": "critical-request-chains",
          "weight": 0
        },
        {
          "id": "user-timings",
          "weight": 0
        },
        {
          "id": "bootup-time",
          "weight": 0
        },
        {
          "id": "mainthread-work-breakdown",
          "weight": 0
        },
        {
          "id": "font-display",
          "weight": 0
        },
        {
          "id": "third-party-summary",
          "weight": 0
        },
        {
          "id": "third-party-facades",
          "weight": 0
        },
        {
          "id": "largest-contentful-paint-element",
          "weight": 0
        },
        {
          "id": "lcp-lazy-loaded",
          "weight": 0
        },
        {
          "id": "layout-shift-elements",
          "weight": 0
        },
        {
          "id": "uses-passive-event-listeners",
          "weight": 0
        },
        {
          "id": "no-document-write",
          "weight": 0
        },
        {
          "id": "long-tasks",
          "weight": 0
        },
        {
          "id": "non-composited-animations",
          "weight": 0
        },
        {
          "id": "unsized-images",
          "weight": 0
        },
        {
          "id": "viewport",
          "weight": 0
        },
        {
          "id": "performance-budget",
          "weight": 0,
          "group": "budgets"
        },
        {
          "id": "timing-budget",
          "weight": 0,
          "group": "budgets"
        },
        {
          "id": "network-requests",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "network-rtt",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "network-server-latency",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "main-thread-tasks",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "diagnostics",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "metrics",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "screenshot-thumbnails",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "final-screenshot",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "script-treemap-data",
          "weight": 0,
          "group": "hidden"
        }
      ]
    },
    "accessibility": {
      "id": "accessibility",
      "title": "Accessibility",
      "description": "These checks highlight opportunities to [improve the accessibility of your web app](https://developer.chrome.com/docs/lighthouse/accessibility/). Automatic detection can only detect a subset of issues and does not guarantee the accessibility of your web app, so [manual testing](https://web.dev/how-to-review/) is also encouraged.",
      "score": 0.94,
      "manualDescription": "These items address areas which an automated testing tool cannot cover. Learn more in our guide on [conducting an accessibility review](https://web.dev/how-to-review/).",
      "auditRefs": [
        {
          "id": "accesskeys",
          "weight": 0,
          "group": "a11y-navigation"
        },
        {
          "id": "aria-allowed-attr",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-allowed-role",
          "weight": 1,
          "group": "a11y-aria"
        },
        {
          "id": "aria-command-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-dialog-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-hidden-body",
          "weight": 10,
          "group": "a11y-aria"
        },
        {
          "id": "aria-hidden-focus",
          "weight": 7,
          "group": "a11y-aria"
        },
        {
          "id": "aria-input-field-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-meter-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-progressbar-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-required-attr",
          "weight": 10,
          "group": "a11y-aria"
        },
        {
          "id": "aria-required-children",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-required-parent",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-roles",
          "weight": 7,
          "group": "a11y-aria"
        },
        {
          "id": "aria-text",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-toggle-field-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-tooltip-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-treeitem-name",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-valid-attr-value",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "aria-valid-attr",
          "weight": 0,
          "group": "a11y-aria"
        },
        {
          "id": "button-name",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "bypass",
          "weight": 0,
          "group": "a11y-navigation"
        },
        {
          "id": "color-contrast",
          "weight": 7,
          "group": "a11y-color-contrast"
        },
        {
          "id": "definition-list",
          "weight": 0,
          "group": "a11y-tables-lists"
        },
        {
          "id": "dlitem",
          "weight": 0,
          "group": "a11y-tables-lists"
        },
        {
          "id": "document-title",
          "weight": 7,
          "group": "a11y-names-labels"
        },
        {
          "id": "duplicate-id-active",
          "weight": 0,
          "group": "a11y-navigation"
        },
        {
          "id": "duplicate-id-aria",
          "weight": 10,
          "group": "a11y-aria"
        },
        {
          "id": "form-field-multiple-labels",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "frame-title",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "heading-order",
          "weight": 3,
          "group": "a11y-navigation"
        },
        {
          "id": "html-has-lang",
          "weight": 7,
          "group": "a11y-language"
        },
        {
          "id": "html-lang-valid",
          "weight": 7,
          "group": "a11y-language"
        },
        {
          "id": "html-xml-lang-mismatch",
          "weight": 0,
          "group": "a11y-language"
        },
        {
          "id": "image-alt",
          "weight": 10,
          "group": "a11y-names-labels"
        },
        {
          "id": "image-redundant-alt",
          "weight": 1,
          "group": "a11y-names-labels"
        },
        {
          "id": "input-button-name",
          "weight": 10,
          "group": "a11y-names-labels"
        },
        {
          "id": "input-image-alt",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "label-content-name-mismatch",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "label",
          "weight": 7,
          "group": "a11y-names-labels"
        },
        {
          "id": "link-in-text-block",
          "weight": 0,
          "group": "a11y-color-contrast"
        },
        {
          "id": "link-name",
          "weight": 7,
          "group": "a11y-names-labels"
        },
        {
          "id": "list",
          "weight": 7,
          "group": "a11y-tables-lists"
        },
        {
          "id": "listitem",
          "weight": 7,
          "group": "a11y-tables-lists"
        },
        {
          "id": "meta-refresh",
          "weight": 0,
          "group": "a11y-best-practices"
        },
        {
          "id": "meta-viewport",
          "weight": 0,
          "group": "a11y-best-practices"
        },
        {
          "id": "object-alt",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "select-name",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "skip-link",
          "weight": 0,
          "group": "a11y-names-labels"
        },
        {
          "id": "tabindex",
          "weight": 0,
          "group": "a11y-navigation"
        },
        {
          "id": "table-duplicate-name",
          "weight": 0,
          "group": "a11y-tables-lists"
        },
        {
          "id": "table-fake-caption",
          "weight": 0,
          "group": "a11y-tables-lists"
        },
        {
          "id": "td-has-header",
          "weight": 0,
          "group": "a11y-tables-lists"
        },
        {
          "id": "td-headers-attr",
          "weight": 0,
          "group": "a11y-tables-lists"
        },
        {
          "id": "th-has-data-cells",
          "weight": 0,
          "group": "a11y-tables-lists"
        },
        {
          "id": "valid-lang",
          "weight": 0,
          "group": "a11y-language"
        },
        {
          "id": "video-caption",
          "weight": 0,
          "group": "a11y-audio-video"
        },
        {
          "id": "focusable-controls",
          "weight": 0
        },
        {
          "id": "interactive-element-affordance",
          "weight": 0
        },
        {
          "id": "logical-tab-order",
          "weight": 0
        },
        {
          "id": "visual-order-follows-dom",
          "weight": 0
        },
        {
          "id": "focus-traps",
          "weight": 0
        },
        {
          "id": "managed-focus",
          "weight": 0
        },
        {
          "id": "use-landmarks",
          "weight": 0
        },
        {
          "id": "offscreen-content-hidden",
          "weight": 0
        },
        {
          "id": "custom-controls-labels",
          "weight": 0
        },
        {
          "id": "custom-controls-roles",
          "weight": 0
        },
        {
          "id": "empty-heading",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "identical-links-same-purpose",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "landmark-one-main",
          "weight": 0,
          "group": "hidden"
        },
        {
          "id": "target-size",
          "weight": 0,
          "group": "hidden"
        }
      ]
    },
    "best-practices": {
      "id": "best-practices",
      "title": "Best Practices",
      "score": 0.95,
      "auditRefs": [
        {
          "id": "is-on-https",
          "weight": 5,
          "group": "best-practices-trust-safety"
        },
        {
          "id": "geolocation-on-start",
          "weight": 1,
          "group": "best-practices-trust-safety"
        },
        {
          "id": "notification-on-start",
          "weight": 1,
          "group": "best-practices-trust-safety"
        },
        {
          "id": "csp-xss",
          "weight": 0,
          "group": "best-practices-trust-safety"
        },
        {
          "id": "paste-preventing-inputs",
          "weight": 3,
          "group": "best-practices-ux"
        },
        {
          "id": "image-aspect-ratio",
          "weight": 1,
          "group": "best-practices-ux"
        },
        {
          "id": "image-size-responsive",
          "weight": 1,
          "group": "best-practices-ux"
        },
        {
          "id": "preload-fonts",
          "weight": 0,
          "group": "best-practices-ux"
        },
        {
          "id": "doctype",
          "weight": 1,
          "group": "best-practices-browser-compat"
        },
        {
          "id": "charset",
          "weight": 1,
          "group": "best-practices-browser-compat"
        },
        {
          "id": "no-unload-listeners",
          "weight": 1,
          "group": "best-practices-general"
        },
        {
          "id": "js-libraries",
          "weight": 0,
          "group": "best-practices-general"
        },
        {
          "id": "deprecations",
          "weight": 5,
          "group": "best-practices-general"
        },
        {
          "id": "errors-in-console",
          "weight": 1,
          "group": "best-practices-general"
        },
        {
          "id": "valid-source-maps",
          "weight": 0,
          "group": "best-practices-general"
        },
        {
          "id": "inspector-issues",
          "weight": 1,
          "group": "best-practices-general"
        }
      ]
    },
    "seo": {
      "id": "seo",
      "title": "SEO",
      "description": "These checks ensure that your page is following basic search engine optimization advice. There are many additional factors Lighthouse does not score here that may affect your search ranking, including performance on [Core Web Vitals](https://web.dev/learn-core-web-vitals/). [Learn more about Google Search Essentials](https://support.google.com/webmasters/answer/35769).",
      "score": 0.67,
      "manualDescription": "Run these additional validators on your site to check additional SEO best practices.",
      "auditRefs": [
        {
          "id": "viewport",
          "weight": 1,
          "group": "seo-mobile"
        },
        {
          "id": "document-title",
          "weight": 1,
          "group": "seo-content"
        },
        {
          "id": "meta-description",
          "weight": 1,
          "group": "seo-content"
        },
        {
          "id": "http-status-code",
          "weight": 1,
          "group": "seo-crawl"
        },
        {
          "id": "link-text",
          "weight": 1,
          "group": "seo-content"
        },
        {
          "id": "crawlable-anchors",
          "weight": 1,
          "group": "seo-crawl"
        },
        {
          "id": "is-crawlable",
          "weight": 1,
          "group": "seo-crawl"
        },
        {
          "id": "robots-txt",
          "weight": 0,
          "group": "seo-crawl"
        },
        {
          "id": "image-alt",
          "weight": 1,
          "group": "seo-content"
        },
        {
          "id": "hreflang",
          "weight": 1,
          "group": "seo-content"
        },
        {
          "id": "canonical",
          "weight": 0,
          "group": "seo-content"
        },
        {
          "id": "font-size",
          "weight": 1,
          "group": "seo-mobile"
        },
        {
          "id": "plugins",
          "weight": 1,
          "group": "seo-content"
        },
        {
          "id": "tap-targets",
          "weight": 1,
          "group": "seo-mobile"
        },
        {
          "id": "structured-data",
          "weight": 0
        }
      ]
    },
    "pwa": {
      "id": "pwa",
      "title": "PWA",
      "description": "These checks validate the aspects of a Progressive Web App. [Learn what makes a good Progressive Web App](https://web.dev/pwa-checklist/).",
      "score": 0,
      "manualDescription": "These checks are required by the baseline [PWA Checklist](https://web.dev/pwa-checklist/) but are not automatically checked by Lighthouse. They do not affect your score but it's important that you verify them manually.",
      "auditRefs": [
        {
          "id": "installable-manifest",
          "weight": 2,
          "group": "pwa-installable"
        },
        {
          "id": "splash-screen",
          "weight": 1,
          "group": "pwa-optimized"
        },
        {
          "id": "themed-omnibox",
          "weight": 1,
          "group": "pwa-optimized"
        },
        {
          "id": "content-width",
          "weight": 1,
          "group": "pwa-optimized"
        },
        {
          "id": "viewport",
          "weight": 2,
          "group": "pwa-optimized"
        },
        {
          "id": "maskable-icon",
          "weight": 1,
          "group": "pwa-optimized"
        },
        {
          "id": "pwa-cross-browser",
          "weight": 0
        },
        {
          "id": "pwa-page-transitions",
          "weight": 0
        },
        {
          "id": "pwa-each-page-has-url",
          "weight": 0
        }
      ]
    }
  },
  "categoryGroups": {
    "a11y-color-contrast": {
      "title": "Contrast",
      "description": "These are opportunities to improve the legibility of your content."
    },
    "metrics": {
      "title": "Metrics"
    },
    "best-practices-ux": {
      "title": "User Experience"
    },
    "pwa-optimized": {
      "title": "PWA Optimized"
    },
    "budgets": {
      "title": "Budgets",
      "description": "Performance budgets set standards for the performance of your site."
    },
    "best-practices-general": {
      "title": "General"
    },
    "a11y-navigation": {
      "title": "Navigation",
      "description": "These are opportunities to improve keyboard navigation in your application."
    },
    "a11y-audio-video": {
      "title": "Audio and video",
      "description": "These are opportunities to provide alternative content for audio and video. This may improve the experience for users with hearing or vision impairments."
    },
    "a11y-names-labels": {
      "title": "Names and labels",
      "description": "These are opportunities to improve the semantics of the controls in your application. This may enhance the experience for users of assistive technology, like a screen reader."
    },
    "best-practices-browser-compat": {
      "title": "Browser Compatibility"
    },
    "seo-crawl": {
      "title": "Crawling and Indexing",
      "description": "To appear in search results, crawlers need access to your app."
    },
    "pwa-installable": {
      "title": "Installable"
    },
    "diagnostics": {
      "title": "Diagnostics",
      "description": "More information about the performance of your application. These numbers don't [directly affect](https://developer.chrome.com/docs/lighthouse/performance/performance-scoring/) the Performance score."
    },
    "seo-content": {
      "title": "Content Best Practices",
      "description": "Format your HTML in a way that enables crawlers to better understand your app’s content."
    },
    "seo-mobile": {
      "title": "Mobile Friendly",
      "description": "Make sure your pages are mobile friendly so users don’t have to pinch or zoom in order to read the content pages. [Learn how to make pages mobile-friendly](https://developers.google.com/search/mobile-sites/)."
    },
    "a11y-best-practices": {
      "title": "Best practices",
      "description": "These items highlight common accessibility best practices."
    },
    "a11y-tables-lists": {
      "title": "Tables and lists",
      "description": "These are opportunities to improve the experience of reading tabular or list data using assistive technology, like a screen reader."
    },
    "a11y-aria": {
      "title": "ARIA",
      "description": "These are opportunities to improve the usage of ARIA in your application which may enhance the experience for users of assistive technology, like a screen reader."
    },
    "a11y-language": {
      "title": "Internationalization and localization",
      "description": "These are opportunities to improve the interpretation of your content by users in different locales."
    },
    "best-practices-trust-safety": {
      "title": "Trust and Safety"
    },
    "load-opportunities": {
      "title": "Opportunities",
      "description": "These suggestions can help your page load faster. They don't [directly affect](https://developer.chrome.com/docs/lighthouse/performance/performance-scoring/) the Performance score."
    }
  },
  "timing": {
    "total": 7959
  },
  "i18n": {
    "rendererFormattedStrings": {
      "varianceDisclaimer": "Values are estimated and may vary. The [performance score is calculated](https://developer.chrome.com/docs/lighthouse/performance/performance-scoring/) directly from these metrics.",
      "opportunityResourceColumnLabel": "Opportunity",
      "opportunitySavingsColumnLabel": "Estimated Savings",
      "errorMissingAuditInfo": "Report error: no audit information",
      "errorLabel": "Error!",
      "warningHeader": "Warnings: ",
      "passedAuditsGroupTitle": "Passed audits",
      "notApplicableAuditsGroupTitle": "Not applicable",
      "manualAuditsGroupTitle": "Additional items to manually check",
      "toplevelWarningsMessage": "There were issues affecting this run of Lighthouse:",
      "crcLongestDurationLabel": "Maximum critical path latency:",
      "crcInitialNavigation": "Initial Navigation",
      "lsPerformanceCategoryDescription": "[Lighthouse](https://developers.google.com/web/tools/lighthouse/) analysis of the current page on an emulated mobile network. Values are estimated and may vary.",
      "labDataTitle": "Lab Data",
      "warningAuditsGroupTitle": "Passed audits but with warnings",
      "snippetExpandButtonLabel": "Expand snippet",
      "snippetCollapseButtonLabel": "Collapse snippet",
      "thirdPartyResourcesLabel": "Show 3rd-party resources",
      "runtimeDesktopEmulation": "Emulated Desktop",
      "runtimeMobileEmulation": "Emulated Moto G Power",
      "runtimeNoEmulation": "No emulation",
      "runtimeSettingsBenchmark": "Unthrottled CPU/Memory Power",
      "runtimeSettingsCPUThrottling": "CPU throttling",
      "runtimeSettingsDevice": "Device",
      "runtimeSettingsNetworkThrottling": "Network throttling",
      "runtimeSettingsUANetwork": "User agent (network)",
      "runtimeUnknown": "Unknown",
      "dropdownCopyJSON": "Copy JSON",
      "dropdownDarkTheme": "Toggle Dark Theme",
      "dropdownPrintExpanded": "Print Expanded",
      "dropdownPrintSummary": "Print Summary",
      "dropdownSaveGist": "Save as Gist",
      "dropdownSaveHTML": "Save as HTML",
      "dropdownSaveJSON": "Save as JSON",
      "dropdownViewer": "Open in Viewer",
      "footerIssue": "File an issue",
      "throttlingProvided": "Provided by environment",
      "calculatorLink": "See calculator.",
      "runtimeSettingsAxeVersion": "Axe version",
      "viewTreemapLabel": "View Treemap",
      "showRelevantAudits": "Show audits relevant to:"
    }
  },
  "entities": [
    {
      "name": "GitHub",
      "category": "utility",
      "isFirstParty": true,
      "origins": [
        "https://jxbang94.github.io"
      ]
    },
    {
      "name": "Bootstrap CDN",
      "homepage": "https://www.bootstrapcdn.com/",
      "category": "cdn",
      "origins": [
        "https://maxcdn.bootstrapcdn.com"
      ]
    },
    {
      "name": "Google CDN",
      "homepage": "https://developers.google.com/speed/libraries/",
      "category": "cdn",
      "origins": [
        "https://ajax.googleapis.com"
      ]
    }
  ],
  "fullPageScreenshot": {
    "screenshot": {
      "height": 1958,
      "width": 981,
      "data": "data:image/webp;base64,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"
    },
    "nodes": {
      "1-3-DIV": {
        "top": 1163,
        "right": 850,
        "bottom": 1243,
        "left": 630,
        "width": 220,
        "height": 80
      },
      "1-19-INPUT": {
        "height": 26,
        "top": 1617,
        "bottom": 1643,
        "right": 337,
        "left": 173,
        "width": 164
      },
      "1-1-DIV": {
        "top": 946,
        "right": 600,
        "left": 380,
        "height": 60,
        "bottom": 1006,
        "width": 220
      },
      "1-26-LINK": {
        "top": 0,
        "left": 0,
        "height": 0,
        "right": 0,
        "width": 0,
        "bottom": 0
      },
      "1-9-IMG": {
        "height": 600,
        "bottom": 652,
        "left": -974,
        "top": 52,
        "width": 980,
        "right": 6
      },
      "1-14-A": {
        "width": 147,
        "right": 980,
        "top": 52,
        "bottom": 652,
        "left": 833,
        "height": 600
      },
      "1-13-A": {
        "left": 0,
        "bottom": 652,
        "top": 52,
        "height": 600,
        "right": 147,
        "width": 147
      },
      "1-15-FORM": {
        "height": 170,
        "width": 720,
        "left": 130,
        "top": 1617,
        "right": 850,
        "bottom": 1787
      },
      "1-5-DIV": {
        "bottom": 1363,
        "left": 630,
        "top": 1263,
        "right": 850,
        "width": 220,
        "height": 100
      },
      "1-12-A": {
        "left": 192,
        "height": 50,
        "top": 1,
        "right": 384,
        "bottom": 51,
        "width": 192
      },
      "1-6-A": {
        "top": 1405,
        "bottom": 1421,
        "right": 826,
        "left": 654,
        "width": 172,
        "height": 16
      },
      "page-2-FOOTER": {
        "height": 80,
        "top": 1807,
        "width": 980,
        "left": 0,
        "bottom": 1887,
        "right": 980
      },
      "1-2-A": {
        "right": 830,
        "top": 1185,
        "bottom": 1221,
        "height": 36,
        "width": 179,
        "left": 650
      },
      "page-0-IMG": {
        "height": 600,
        "right": 6,
        "bottom": 652,
        "left": -974,
        "top": 52,
        "width": 980
      },
      "1-11-A": {
        "left": 125,
        "height": 50,
        "top": 1,
        "bottom": 51,
        "width": 67,
        "right": 192
      },
      "1-22-INPUT": {
        "right": 190,
        "height": 26,
        "width": 60,
        "left": 130,
        "bottom": 1787,
        "top": 1761
      },
      "page-3-DIV": {
        "height": 136,
        "right": -190,
        "left": -778,
        "bottom": 632,
        "width": 588,
        "top": 496
      },
      "1-27-META": {
        "bottom": 0,
        "top": 0,
        "width": 0,
        "right": 0,
        "left": 0,
        "height": 0
      },
      "1-16-LABEL": {
        "top": 1620,
        "right": 173,
        "height": 20,
        "bottom": 1640,
        "left": 130,
        "width": 43
      },
      "1-17-LABEL": {
        "top": 1668,
        "left": 130,
        "right": 172,
        "height": 20,
        "width": 42,
        "bottom": 1688
      },
      "1-0-A": {
        "left": 441,
        "bottom": 984,
        "height": 16,
        "width": 98,
        "right": 539,
        "top": 968
      },
      "1-25-IMG": {
        "top": 1127,
        "height": 147,
        "width": 220,
        "left": 130,
        "right": 350,
        "bottom": 1273
      },
      "page-1-MAIN": {
        "right": 980,
        "bottom": 1807,
        "width": 980,
        "left": 0,
        "top": 693,
        "height": 1114
      },
      "1-10-A": {
        "height": 50,
        "width": 124,
        "left": 1,
        "top": 1,
        "right": 125,
        "bottom": 51
      },
      "1-24-IMG": {
        "height": 165,
        "top": 713,
        "left": 380,
        "right": 600,
        "bottom": 878,
        "width": 220
      },
      "1-8-H3": {
        "right": -190,
        "height": 26,
        "width": 588,
        "bottom": 562,
        "top": 536,
        "left": -778
      },
      "1-4-A": {
        "left": 657,
        "top": 1285,
        "right": 823,
        "height": 56,
        "bottom": 1341,
        "width": 166
      },
      "1-23-IMG": {
        "width": 980,
        "right": 986,
        "height": 551,
        "bottom": 603,
        "top": 52,
        "left": 6
      },
      "1-21-INPUT": {
        "bottom": 1739,
        "width": 164,
        "height": 26,
        "right": 376,
        "left": 212,
        "top": 1713
      },
      "1-7-DIV": {
        "height": 60,
        "width": 220,
        "right": 850,
        "left": 630,
        "bottom": 1443,
        "top": 1383
      },
      "1-18-LABEL": {
        "height": 20,
        "top": 1716,
        "left": 130,
        "width": 82,
        "right": 212,
        "bottom": 1736
      },
      "1-20-INPUT": {
        "bottom": 1691,
        "top": 1665,
        "width": 164,
        "right": 336,
        "left": 172,
        "height": 26
      },
      "1-28-META": {
        "bottom": 0,
        "top": 0,
        "width": 0,
        "right": 0,
        "left": 0,
        "height": 0
      },
      "page-4-P": {
        "width": 750,
        "top": 816,
        "height": 120,
        "left": 115,
        "right": 865,
        "bottom": 936
      }
    }
  }
}
