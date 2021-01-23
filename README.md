}
  "settings": {
    "name": "token",
    "currentPage": "index.html",
    "theme": {
      "name": "mobirise4",
      "title": "Mobirise 4",
      "styling": {
        "primaryColor": "#149dcc",
        "secondaryColor": "#ff3366",
        "successColor": "#F7ED4A",
        "infoColor": "#82786E",
        "warningColor": "#879A9F",
        "dangerColor": "#B1A374",
        "mainFont": "Rubik",
        "display1Font": "Rubik",
        "display1Size": 4.25,
        "display2Font": "Rubik",
        "display2Size": 3,
        "display5Font": "Rubik",
        "display5Size": 1.5,
        "display7Font": "Rubik",
        "display7Size": 1,
        "display4Font": "Rubik",
        "display4Size": 1,
        "isRoundedButtons": true,
        "isAnimatedOnScroll": false,
        "isScrollToTopButton": false
      },
      "additionalSetColors": [
        "#000000",
        "#c1bbbd"
      ]
    },
    "path": "@PROJECT_PATH@",
    "siteFonts": [],
    "versionFirst": "4.7.5",
    "uniqCompNum": 17,
    "versionPublish": "4.7.5",
    "favicon": "",
    "noImageResize": ""
  },
  "pages": {
    "index.html": {
      "settings": {
        "main": true,
        "title": "Home",
        "meta_descr": "",
        "header_custom": "",
        "footer_custom": "",
        "html_before": ""
      },
      "components": [
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "letter-spacing": ".2rem"
            }
          },
          "_name": "header10",
          "_customHTML": "<section class=\"header10\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/baground.jpg-1920x1920.jpg\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#c1bbbd\">\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"media-container-column mbr-white col-lg-8 col-md-10 ml-auto\">\n            <h1 class=\"mbr-section-title align-right mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\"></h1>\n            <h3 class=\"mbr-section-subtitle align-right mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">TRICKS TOKEN</h3>\n            <p class=\"mbr-text align-right pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">TRICKS token is a utility token for           the  De-Fi and Decentralized            <br> platforms. TRICKS token is developed by a group of people who want to share the equal great opportunity to the holders through a decentralized network.&nbsp;</p>\n            <div class=\"mbr-section-btn align-right\" mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\"><a class=\"btn btn-md btn-primary\" href=\"https://mobirise.com\">Whitepaper</a>\n                <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.com\">Token Contrack</a></div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "smUXg8IKOg",
          "_anchor": "header10-c",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "background-color": "@bgColor",
            ".line": {
              "background-color": "@lineColor",
              "color": "@lineColor",
              "align": "center",
              "height": "2px",
              "margin": "0 auto"
            },
            ".section-text": {
              "padding": "2rem 0"
            },
            ".inner-container": {
              "margin": "0 auto"
            },
            "@media (max-width: 768px)": {
              ".inner-container": {
                "width": "100% !important"
              }
            }
          },
          "_name": "content9",
          "_customHTML": "<section class=\"mbr-section article content9\" group=\"Article\">\n    \n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"2\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"2\">\n        <input type=\"range\" inline title=\"Text Width\" name=\"innerWidth\" min=\"50\" max=\"100\" step=\"1\" value=\"100\">\n        <input type=\"range\" inline title=\"Line Width\" name=\"lineLength\" min=\"10\" max=\"100\" step=\"1\" value=\"25\">\n        <input type=\"color\" title=\"Line Color\" name=\"lineColor\" value=\"#149dcc\">\n        <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#ffffff\">\n    <!-- End block parameters -->\n    </mbr-parameters> \n\n    <div class=\"container\">\n        <div class=\"inner-container\" mbr-style=\"{'width': innerWidth + '%'}\">\n            <hr class=\"line\" mbr-style=\"{'width': lineLength + '%'}\">\n            <div class=\"section-text align-center mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".section-text\" mbr-text>The TRICKS token is a token that can only be used actively on a decentralized application (DApp) which is a transparent and trusted sports betting. Additionally, it is the first decentralized bet for sports on the TRON network. Enjoy betting experience tokens at Liquidity Pool. Therefore, you are entitled to create TRICKStokens based on the current APY. Transparent calculations are carried out in the background in a systematic manner without human intervention and pure mathematical logarithms and a mix of financial investments.</div>\n            <hr class=\"line\" mbr-style=\"{'width': lineLength + '%'}\">\n        </div>\n        </div>\n</section>",
          "_cid": "smUYlEX8yE",
          "_anchor": "content9-d",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "color": "#767676"
            },
            ".container-table": {
              "margin": "0 auto"
            },
            ".scroll": {
              "overflow-x": "auto",
              "padding": "0"
            },
            ".dataTables_wrapper": {
              "display": "block",
              ".search": {
                "margin-bottom": ".5rem"
              },
              ".table": {
                "overflow-x": "auto"
              }
            },
            "table": {
              "width": "100% !important",
              "margin-top": "6px",
              "border": "1px solid @tbColor",
              "margin-bottom": "0",
              "th": {
                "border-top": "none",
                "transition": "all .2s",
                "border-bottom": "none",
                "&:hover": {
                  "background": "@tbColor",
                  "color": "contrast(@tbColor)"
                }
              },
              "td": {
                "border-top": "1px solid @tbColor"
              },
              "&.table": {
                "& when (@tbBackground)": {
                  "background": "@tbBgColor"
                }
              }
            },
            ".dataTables_filter": {
              "text-align": "right",
              "margin-bottom": ".5rem",
              "label": {
                "display": "inline",
                "white-space": "normal !important"
              },
              "input": {
                "display": "inline",
                "width": "auto",
                "margin-left": ".5rem",
                "border-radius": "100px",
                "padding-left": "1rem"
              }
            },
            ".dataTables_info": {
              "padding-bottom": "1rem",
              "padding-top": "1rem",
              "white-space": "normal !important"
            },
            "@media (max-width: 992px)": {
              ".dataTables_filter": {
                "text-align": "center"
              }
            },
            "@media (max-width: 350px)": {
              ".dataTables_filter": {
                "text-align": "center",
                "input": {
                  "width": "100% !important",
                  "margin-left": "0 !important"
                }
              }
            }
          },
          "_name": "table1",
          "_customHTML": "<section class=\"section-table\" group=\"Tables\" plugins=\"dataTables\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n  <mbr-parameters>\n  <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n    <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n    <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n    <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n    <input type=\"range\" inline title=\"Columns\" name=\"tableColumns\" min=\"1\" max=\"50\" step=\"1\" value=\"4\">\n    <input type=\"range\" inline title=\"Rows\" name=\"tableRows\" min=\"1\" max=\"50\" step=\"1\" value=\"4\">\n    <input type=\"color\" title=\"Table Border Color\" name=\"tbColor\" value=\"#cccccc\">\n    <input type=\"checkbox\" title=\"Table Background\" name=\"tbBackground\" checked>\n    <input type=\"color\" title=\"Table Background Color\" name=\"tbBgColor\" value=\"#ffffff\" condition=\"tbBackground\">\n    <input type=\"checkbox\" title=\"Search\" name=\"isSearch\">\n    <fieldset type=\"background\" name=\"bg\" parallax>\n      <input type=\"image\" title=\"Background Image\" value=\"../_images/background1.jpg\" parallax>\n      <input type=\"color\" title=\"Background Color\" value=\"#f9f9f9\" selected>\n      <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n    </fieldset>\n    <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n    <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#ffffff\" condition=\"overlay && bg.type !== 'color'\">\n    <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.7\" condition=\"overlay && bg.type !== 'color'\">    \n  <!-- End block parameters -->\n  </mbr-parameters>\n  <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n  </div>\n  <div class=\"container container-table\">\n      <h2 class=\"mbr-section-title mbr-fonts-style align-center pb-3\" mbr-theme-style=\"display-2\" data-app-selector=\".mbr-section-title\" mbr-if=\"showTitle\"></h2>\n      <h3 class=\"mbr-section-subtitle mbr-fonts-style align-center pb-5 mbr-light\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-section-subtitle\">TOKEN CONTRACK</h3>\n      <div class=\"table-wrapper\">\n        <div class=\"container\">\n          <div class=\"row search\" mbr-if=\"isSearch\">\n            <div class=\"col-md-6\"></div>\n            <div class=\"col-md-6\">\n                <div class=\"dataTables_filter\">\n                  <label mbr-text class=\"searchInfo mbr-fonts-style\" mbr-theme-style=\"display-7\">Search:</label>\n                  <input class=\"form-control input-sm\" disabled>\n                </div>\n            </div>\n          </div>\n        </div>\n\n        <div class=\"container scroll\">\n          <table class=\"table\" mbr-class=\"{'isSearch':isSearch}\" cellspacing=\"0\">\n            <thead>\n              <tr class=\"table-heads \" mbr-list mbr-list-grow=\"tableColumns\">\n                  <th mbr-text class=\"head-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".head-item\"></th>\n                  <th mbr-text class=\"head-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".head-item\"></th>\n                  <th mbr-text class=\"head-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".head-item\"></th>\n                  <th mbr-text class=\"head-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".head-item\"></th>\n              </tr>\n            </thead>\n\n            <tbody mbr-list mbr-list-grow=\"tableRows\">\n              <tr mbr-list mbr-list-grow=\"tableColumns\"> \n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">Name&nbsp;</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">:&nbsp; &nbsp;Tricks</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"></td>\n              </tr>\n              <tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">Decimal</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">:</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"></td>\n              </tr>\n              <tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">Symbol</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">:</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"></td>\n              </tr>\n              <tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">Supply</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">:</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"></td>\n              </tr>\n            </tbody>\n          </table>\n        </div>\n        <div class=\"container table-info-container\">\n          <div class=\"row info\" mbr-if=\"isSearch\">\n            <div class=\"col-md-6\">\n              <div class=\"dataTables_info mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <span mbr-text class=\"infoBefore\" data-app-selector=\".dataTables_info\">Showing</span>\n                <span class=\"inactive infoRows\"></span>\n                <span mbr-text class=\"infoAfter\" data-app-selector=\".dataTables_info\">entries</span>\n                <span mbr-text class=\"infoFilteredBefore\" data-app-selector=\".dataTables_info\">(filtered from</span>\n                <span class=\"inactive infoRows\"></span>\n                <span mbr-text class=\"infoFilteredAfter\" data-app-selector=\".dataTables_info\"> total entries)</span>\n              </div>\n            </div>\n            <div class=\"col-md-6\"></div>\n          </div>\n        </div>\n      </div>\n    </div>\n</section>",
          "_cid": "smV1YbflnI",
          "_anchor": "table1-e",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "color": "#767676",
              "text-align": "center",
              "font-weight": "300"
            },
            ".timeline-text-content": {
              "padding": "2rem 2.5rem",
              "background": "@timelineColor",
              "margin-left": "2rem",
              "p": {
                "margin-bottom": "0"
              }
            },
            ".time-line-date-content": {
              "margin-right": "2rem",
              "p": {
                "padding": "2rem 2.5rem",
                "background": "@timelineColor",
                "float": "right"
              }
            },
            ".timeline-element": {
              "margin-bottom": "50px",
              "position": "relative",
              "word-wrap": "break-word",
              "word-break": "break-word",
              "display": "-webkit-flex",
              "flex-direction": "row",
              "-webkit-flex-direction": "row",
              "&:hover": {
                ".mbr-timeline-date": {
                  "box-shadow": "0 7px 20px 0px rgba(0, 0, 0, 0.08)",
                  "transition": "all .4s"
                },
                ".timeline-text-content": {
                  "box-shadow": "0 7px 20px 0px rgba(0, 0, 0, 0.08)",
                  "transition": "all .4s"
                }
              }
            },
            ".mbr-timeline-date, .timeline-text-content": {
              "transition": "all .4s"
            },
            ".reverse": {
              "flex-direction": "row-reverse",
              "-webkit-flex-direction": "row-reverse",
              ".timeline-text-content": {
                "margin-right": "2rem",
                "margin-left": "0"
              },
              ".time-line-date-content": {
                "margin-left": "2rem",
                "margin-right": "0rem",
                "p": {
                  "float": "left"
                }
              }
            },
            ".iconBackground": {
              "position": "absolute",
              "left": "50%",
              "width": "20px",
              "height": "20px",
              "line-height": "30px",
              "text-align": "center",
              "border-radius": "50%",
              "font-size": "30px",
              "display": "inline-block",
              "background-color": "@timelineColor",
              "top": "20px",
              "margin-left": "-10px"
            },
            ".separline:before": {
              "top": "20px",
              "bottom": "0",
              "position": "absolute",
              "content": "\"\"",
              "width": "2px",
              "background-color": "@timelineColor",
              "left": "calc(50% ~\"-\" 1px)",
              "height": "calc(100% ~\"+\" 4rem)"
            },
            "@media (max-width: 768px)": {
              ".iconBackground": {
                "left": "0 !important"
              },
              ".separline:before": {
                "left": "0!important"
              },
              ".timeline-text-content": {
                "margin-left": "0 !important"
              },
              ".time-line-date-content": {
                "margin-right": "0 !important",
                "p": {
                  "float": "left !important"
                }
              },
              ".reverse": {
                ".time-line-date-content": {
                  "margin-left": "0 !important"
                },
                ".timeline-text-content": {
                  "margin-right": "0 !important"
                }
              }
            }
          },
          "_name": "timeline1",
          "_customHTML": "<section class=\"timeline1\" group=\"Timelines\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel)-->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n        \n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show Dates\" name=\"showDates\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n        \n        <input type=\"color\" title=\"Timelines Color\" name=\"timelineColor\" value=\"#ffffff\">\n        <select title=\"Timelines count\" name=\"timelinesAmount\">\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\" selected>3</option>\n            <option value=\"4\">4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\">6</option>\n            <option value=\"7\">7</option>\n            <option value=\"8\">8</option>\n            <option value=\"9\">9</option>\n            <option value=\"10\">10</option>\n            <option value=\"11\">11</option>\n            <option value=\"12\">12</option>\n        </select>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/img/03.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#f8f8f8\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" checked condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#cccccc\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.9\" condition=\"overlay && bg.type !== 'color'\">\n        <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container align-center\">\n        <h2 class=\"mbr-section-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title\">Roadmap</h2>\n        <h3 class=\"mbr-section-subtitle pb-5 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-section-subtitle\"></h3>\n\n        <div class=\"container timelines-container\" mbri-timelines>\n            <div class=\"row timeline-element reverse\" mbr-class=\"{'separline':timelinesAmount>1}\">      \n                 <div class=\"timeline-date-panel col-xs-12 col-md-6  align-left\">         \n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">Januari 2021</p>\n                    </div>\n                </div>\n           <span class=\"iconBackground\"></span>\n            <div class=\"col-xs-12 col-md-6 align-right\">\n                <div class=\"timeline-text-content\">\n                    <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">publish the MATCH platform to achieve its objectives.</h4>\n                    <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\"></p>\n                 </div>\n            </div>\n            </div>\n\n            <div class=\"row timeline-element \" mbr-if=\"timelinesAmount>1\" mbr-class=\"{'separline':timelinesAmount>2}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6 align-right\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">April 2021</p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-left \">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">Tricks tokens will be listed on JustSwap. Trickstoken holders will be able to exchange tricks tokens into other currencies listed on JustSwap.</h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\"></p>\n                    </div>\n                </div>\n            </div> \n\n\n            <div class=\"row timeline-element reverse\" mbr-if=\"timelinesAmount>2\" mbr-class=\"{'separline':timelinesAmount>3}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6  align-left\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">Mei 2021&nbsp; &nbsp; &nbsp;</p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-right\">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">Introducing a further stage 2 decentralized campaign, several campaigns will be held.</h4>      \n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\"></p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"row timeline-element \" mbr-if=\"timelinesAmount>3\" mbr-class=\"{'separline':timelinesAmount>4}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6 align-right\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                            4 april 2021\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-left \">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Design out of the box\n                        </h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n\n\n            <div class=\"row timeline-element reverse\" mbr-if=\"timelinesAmount>4\" mbr-class=\"{'separline':timelinesAmount>5}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6  align-left\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                            5 may 2022\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-right\">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Awesome Reports\n                        </h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n\n\n            <div class=\"row timeline-element\" mbr-if=\"timelinesAmount>5\" mbr-class=\"{'separline':timelinesAmount>6}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6 align-right\">\n                    <div class=\"time-line-date-content\">\n                       <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                            6 june 2023\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-left \">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Multi Homepages\n                        </h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"row timeline-element reverse\" mbr-if=\"timelinesAmount>6\" mbr-class=\"{'separline':timelinesAmount>7}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6  align-left\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                           7 july 2024\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-right\">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Responsive Design\n                        </h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"row timeline-element\" mbr-if=\"timelinesAmount>7\" mbr-class=\"{'separline':timelinesAmount>8}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6 align-right\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                           8 august 2025  \n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-left \">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Smart Watch\n                        </h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"row timeline-element reverse\" mbr-if=\"timelinesAmount>8\" mbr-class=\"{'separline':timelinesAmount>9}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6  align-left\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                           9 september 2026\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-right\">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Design out of the box\n                        </h4>\n\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"row timeline-element\" mbr-if=\"timelinesAmount>9\" mbr-class=\"{'separline':timelinesAmount>10}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6 align-right\">\n                    <div class=\"time-line-date-content\">\n                       <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                          10 october 2027\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-left \">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Awesome Reports\n                        </h4> \n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"row timeline-element reverse\" mbr-if=\"timelinesAmount>10\" mbr-class=\"{'separline':timelinesAmount>11}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6  align-left\">\n                    <div class=\"time-line-date-content\">\n                       <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                          11 november 2028\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-right\">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Design out of the box\n                        </h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"row timeline-element\" mbr-if=\"timelinesAmount>11\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6 align-right\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                           12 december 2029\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-left \">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Awesome Reports\n                        </h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "smV3ENCfyn",
          "_anchor": "timeline1-f",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(0deg, @color2, @bg-value)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-iconfont-social": {
              "font-size": "32px",
              "color": "@iconsColor"
            },
            ".social-list": {
              "a:focus": {
                "text-decoration": "none"
              }
            }
          },
          "_name": "social-buttons2",
          "_customHTML": "<section group=\"Social\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" plugins=\"SocialLikes\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input inline type=\"range\" title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n        <input inline type=\"range\" title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        \n        <input type=\"color\" title=\"Icons Color\" name=\"iconsColor\" value=\"#ff3366\"> \n        <select title=\"Icons\" name=\"iconsCount\">\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\" selected>4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\">6</option>\n        </select>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background1.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#6670a9\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"color2\" name=\"color2\" condition=\"bg.type=='color'\" value=\"#7fdbfd\">\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" checked condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#7cd1f6\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"col-md-8 align-center\">\n                <h2 class=\"pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\">\n                    FOLLOW US!\n                </h2>\n                <div class=\"social-list pl-0 mb-0\">\n                    <a href=\"https://twitter.com/mobirise\" target=\"_blank\">\n                        <span mbr-icon class=\"px-2 socicon-twitter socicon mbr-iconfont mbr-iconfont-social\"></span>\n                    </a>\n                    <a href=\"https://www.facebook.com/pages/Mobirise/1616226671953247\" target=\"_blank\">\n                        <span mbr-icon class=\"px-2 mbr-iconfont mbr-iconfont-social socicon-linkedin socicon\" mbr-if=\"iconsCount > 1\"></span>\n                    </a>\n                    <a href=\"https://instagram.com/mobirise\" target=\"_blank\">\n                        <span mbr-icon class=\"px-2 mbr-iconfont mbr-iconfont-social socicon-medium socicon\" mbr-if=\"iconsCount > 2\"></span>\n                    </a>\n                    <a href=\"https://www.youtube.com/c/mobirise\" target=\"_blank\">\n                        <span mbr-icon class=\"px-2 mbr-iconfont mbr-iconfont-social socicon-telegram socicon\" mbr-if=\"iconsCount > 3\"></span>\n                    </a>\n                    <a href=\"https://plus.google.com/u/0/+Mobirise\" target=\"_blank\">\n                        <span mbr-icon class=\"px-2 socicon-googleplus socicon mbr-iconfont mbr-iconfont-social\" mbr-if=\"iconsCount > 4\"></span>\n                    </a>\n                    <a href=\"https://www.behance.net/Mobirise\" target=\"_blank\">\n                        <span mbr-icon class=\"px-2 socicon-behance socicon mbr-iconfont mbr-iconfont-social\" mbr-if=\"iconsCount > 5\"></span>\n                    </a>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "smV7TuQcRA",
          "_anchor": "social-buttons2-g",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    }
  }
}
