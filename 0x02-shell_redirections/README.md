# Shell, I/O Redirections and filters
<p><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAYgAAACACAMAAAAmuQ7NAAABUFBMVEX///8AAAAaGhrm5uYtm/CxsbHg4ODp6emoqKj+9EUMp4mgoKAYGBhtbW3Nzc12dnYyMjI9PT3V1dWUlJTy8vLBwcH29vYODg7c3NzS0tKCgoLHx8elpaWamppfX1+7u7shISFXV1eMjIxNTU0rKyuHh4dFRUVoaGg4ODgnJycAABhQUFBbW1t7e3s8PDz//EcAooIZDgAaExWooTQaDREbJCwgRmQZCgAaEgBjsfMaFxMtmOsPjnUTExkXPzcLDBl5dSshIRsWGh4hU3seO1Mpf8IlaZ8phcsjXIm02flGpvLf7/0dLj0gl/CUyveEwfUZLSgScV8bAAwRgWsUX1Gx4NfP7Obg9O8VVkk+tp5mv6oXOzNYvKYkIxBeXVJ1dW04Ny2Li4JCQiFkYSZWVCTk3UHSzD2Efy2/uzk1Mx+urDZJSCLx6EPc0z5gXSaemTKobeExAAAbmUlEQVR4nO1dZ4PjtpkGSJOgzSoWsIlVFCmNRG3xumSz6/WuU3y53F1cYsfOJXbcnTjn///tAJBqM9Koa3aSedaeoSiOIL4P8VYUAO5whzvc4Q4E2HQS4YRwfHTTt3gL4EW9FJ4aSif3b/pGX25oGYSuwp0aigthJ7npm315IWbnYKGFCyfhbl9PE8kPdc6f5h339l8aSNCdPq4n100NFfnW302sdc/o+YLaS5Cu85oFVK/T004ojZtDn4nHhYVKzKl4OpiOkA8gpFTAGG/55SQjBKXAK2bmVJEwTsbA5TPhpPK4KahUNArshdvK5iCYOut+sLNta4nr9UI+BbrTc7xSGAOIxs4ODWJtH9yASxFQHtzh+R4yv6QtwtF2VyfxgLcKRy1LRxsMEn6YFSga7sBEZz8devZOJzRSOaeDjyvWZn+7q23SdZr/AKa/cftiWyhw0NkZKbT2ubMDwFNvCVZnbjVnTOyiYPbHXu2oZyeCPpxueeZGG7vkTs5ilG4HET4RiFKcP/GAe8Riw+45mrodRNAOcX67BJonwB1cPstj7CFgL57y5PmxbJIfyGs70mJ/wsBe9zTdCiLQzSgmCp0+ApecRGTgQtWRIQA/sbHmk7AtlGKgJRhrHo9C6rZ2C3Xo8T5w7DhCmqkBU8ShXQriutu4FURIVBo3k/rxaNPB8jlZBuTbCG4EgipGsM+ZVjmugB6rSOk5hc4RkUIPWIGkAqhxtegGhhN0xTQkclPX5E1uBRE61dQ3lJouFE4xlk8FDkBqLBbAK/sdfgj0pNTMyu/VJUptbwhUB2DydSVV0AG0ByLgcJT3Bb7ALvHE1mjYW0HEQLkpzeRFBvfixYtBJSxYhDzh+3LhuZJcygbPYTXR1VqVM6tDiECwmxKR6llXCRMjgnYnF1OrI1jjIMWuDII1Pfs2EIFJEOHq52yxhdBr0380z6ib09NhBbqWB4QIR4lgyyDxbMsRMP1fxkCLEpp1FXJiOmShi81cLOQuINd2gWPhHr+6rdtAhEj19LkjF9Jsr8n2tiUKOP8K9W5qEqfz681ozUW3gQiTEiGds0WKpKHh8eMHDx48bqgo7c1/tgrb8HZriDh3FCEwpfT4wRtvvvf+e796zLiAgz2Z2AJ3RKyGz3h461e/foXhl795423KRHayBk9NBLVwuLQrcfdW5p9xfiLwkOilx2+3NDAq3nyLMrFOxe8AP1iVvDolEWYuhDAHUlTYOt8V8n0jgRsgIoLUOvz2lUW8/xa1E4eHMz6E/aufckoiOnqiKZqWdjk0IbFPoO7eEsP5icApUUwP2v7wX7/4RXPw5oPtyxPXwKcFnfyyF3tKIryRyqdAqMEAdbzSS8a7t8RwfiIS2iHebHvCfwDcaifqOg0OToqbTW0tWO4VpySi3y94tzah7iLDHJjJllXHKzg/ETVp8a1GMf3uP8GUiFfeo13i4DEy5rTMqS9ScdIe4SDgacD0fKxhzUb7VrrPT0TP5R7/vtFL/w3+Z0bErx+s/iJ4AfYcaAH8HM684hzMfZg793UFsKHMNdPvXpkR8dsHjd/kcAXFkCKlYPEegdtgh+L/rFfcEbECeKhwD96buUszIn75uCEi2W/ExWqMm15xR8QKLPWIBSJ+S4I6KB+ZiGGTvDkpEQsJAXyAs3GTNmKJiKmNOCIRw24rmKMRIWthpoPFtD1AcH5skR5tXWpKwP52geHZidDnXtMiEVOvyR/FcVxRqEvQp6gpAoY+QU5hMURR1J/TkM5TmcciAhlgmGg+HCErloGaxzyqdA6wF5GUxCNChC6EQRUBNajsKLFVH2bI2CaLdn4i6HC2uZEAoDURbzzmlMnBHy5OaSiEBTVxLCLCGkQDx1ZMIAXQVpw8yvXQJS9clFqiG+qMCKHkoe06ea537aHteqDepnXv7CVr+wWJrGeZpmlk/d7bR4msvbY3dJe09bGIcHKAETRTpKWiglIkWbVMaOHEIUp5DG2rIaICis153bqWxYLWda3NDzo2+26auqp5lnFeLU6Za2I9Qrk8WOpYRJgxLjsZiCeOoRbI5bu5yVWpXVQGckVQD3qECJUSAe2il3oJNy7BeIJic9XnL8DXh80IeRem6hmnGxQ0+/r4JNlXQsSKsdRHM9Ylj8nDQv63iYOEqJdk03/sBWC/6Q+bvIJ06BV9E9u8cfXDF4H0tmjcFo6rNQXf40Oj7T5+8GbbKX75m98frR4hct0VnftoRKCtZbSQYtnwR2EKWw6Uhg4Id5xNtT/aCt1bb7z3/m/ef7Ot0BXHqNCt9uRf5oAuYbJQHj3k0pR7SH5RHX0278lpa9YPHjx4u61Zj05XKX0ZiMCj1cJtqpWP/vDBk/uvvXb/yQd/+JBJY833TUZZFhMNjsfkd8BSpKE+bo9wt8pUCfDkmqwXAjsfj2vStwRydpWaaOCVcHHm5C4z6vYAt09nP3KPGMJ0VUqT2kvlww9em+GDDxWqpVY/lhJMBxBWACvugKgwkcSPxEVslBnuEacdQuI4upNB4QAi4SFUQZedveYpF8jbs/mTW1R7mTNh7OdXKTDWd8bguESQ24WudPnJpDUBRXny2gKecOunq0jkgUUctDGX0r+NiHPiamwmKgYBzDBxgwkRbGC3CDvEPNlgBInPdn15wYvKFy+4F4M42aSVzFo2oY7lPEVeLQE5kaRE3vA3i+D2S5EcdcpA0cSZy0qCzRF69BEj4D77jzLxkCqnlY8mJQIXjAhMwoCIPO+sNDuAGjBg4yV70KCmEkGO6bcKrizjL0OEL7aKJnuqJrp+aDguXwgdZ1yJaraLu+11pSsQskWZ51cvkISjBldG29KSW0dDqkcfNz3hjwD8sTn6+NG6QX8SjBMVlgBzXNdKocd6BUEGJQzT5oOJaiLNIPLZkFgK4BGnbGNc4G2ZXxH1ke0CQQeFB+vAH5mgOjwZ0F8kYlPIBeYVqlXFqXllik1i9ghMCt/3mxmqYTictaVEMw1QukQPsX5w/4/gk0/AJ02feLhq4giFRP++IxIiiLA5jU5DZYRlUMAuNyUi7Qc1OfbJoyaR7913N84a3ZaIICjsQWwqlYv0SuVLE8SHExEsErG5wImNdNjWqeZlqv1UHnlEGyps4rE8/FPTDTC+f/9T0Bz/6SGxnKt0kwR1j54nqsmMqWslwJh9N3IDRnsTrY2gSKidIJai3PSgbUsEMkmM6gFEQyPyRUQM+MOd3V2JOO6aDGx4Ax14/KjxmD4jvYH0is/Zi4+IDwtX6V6p9S6pjUAuh4glgF1sB8QskPvpEdE4UyI8mQch0WKWBuzesYg4CXYlYk+LvxpNHkYj9//hR0tEMN305MM1E26lNi+KXdcmvaFHuwSF6zXuK/EG2rxnwgYWEeGy52fTGJ8bJWJHG3HMHjFoFSutQTz6aE2PWBX6hGojLaxTI9CnCUJeruu2UuUEumUCnvreqg+SQM8JP6alr5s2MsdNEKF1r/Wa1gcqbT2q3yBfKEjRilQUyRRdgubjGyQtHKeYtTWZ3TGaO02fgU/v3/8EfNYEddRt2sJ/OBp2IGIxiXSIfUAbHtb4gM++FoO2gWLhfjHxmR7+uTHQn4LPPwefNsfvEGOtnHM6nbi6KsX3bbXnoKU3snnh04bEWI+zS0kRdUuvP7pUgl1GdbJqwOAKDQSqy3EPm7j6f+nr1kSQDuGe7Im4CjsM/vKX53/5a/eyoxY43ZGNxm7kZT0+Ucs+sMpJ4o17ohOMxFE1xCRM0ZBfj0I1M/tGBOJaio5QzTgEaENecUJoMC7HiA55Eh++0wTWn33++Wf3p97rGaum/BfPWT2ErSy3nEwY8fY4s6MciLWRJ2Mx9SDKBL4e5I7Bd1WTRC6eUgm+K5rQDwvbMIsu9vYd/XskBBtEN4DK1YlZdJDXLLS+f3+a9iNSSU+YjF7CFwtVKRImPl98nkpkg1yXclAKQZ4EuDAhieAyIeg7NZD7tkKIMOgahMAsQTgAE21oA753pm++BgHkrn0/Wzk/ji0M9OHHi0m/j2ki/DxLYxDj8CWrSilPnz17+rSpR/xt/m5sSpwRmlwkl7GV9PHE1o2RQ184ARCNcYmBmA5rPwYekX6V6niAQFKf56uvgw3htZW4NSaMLZf06M+z/OuTPz867eypJWguTYA/vXj21dfvfvPjxQXtG/Cvs7eJuPF0habmX7NU0/SQvrDt2Xmb/Rqd091bAQ/uNfYBG5SJhx++88FHT5589ME7rETnnmmNGv4xrYZcfPX6t/cIXv3u+6fPKBNfzC7YZ3T+DfMgpnt6vogt5sY9fMTwkBWtJ2caPlC6tDv8/Oq9Vxvc++mbC+5coZ1oydYyaXguQWdfpxEPYWfPpxjXi1POqcHc1hM/FNRAKRc/TGlgeJcwoTw//AugjV4fSmAXmXUC5ESQhL4WhEDHUbeP7Ty3k30Xw3DgcH83JyyJ59KswkB8yPMtTvwlafPidcYDU00M3zw7ygoIPJxsvA8XYS40xE7ljfK6J3B4iBQploCV9Z19icgP++6hPmi6w0A/z+J6FDSIefYNk/8/37149mPTNb59pnBu5+AP5xdSamuAXZ6HleoRT6unCRbi7AIVdiQHar/em4jo8nJHOyN0z70ExN8IERf/ZP3hq4tvvn528S07fpd2iYONFM8SCZ3rBm1g0spYr+0hD8pQ6vPQHqIUWXI+jmtn30dBg6uLzNvj/KPBM5d7+mOjkL794dV7X1/8nb6498PFMeL66Wjw8hoqTOL4+h795WHEE3eL/kMI+DZv7z2bMjt0gNz5ZwwRE/Hs65mlvvePi+8aUi6aGUMocQjCFs2SxL7PKsCe59GKMC0N00IxLRtjvDy2bzYsH/bOp2wZCnhYRHl+IgpCxLszz/Xni6+bo5+IkWCTGbevr7TTG5UWHJemi9tfjM66jLu2IbLehJvtEfdev/jqp1eXesQORGzEWVfUHx0mxvPbCBLOPf3HvSkP30zDuu9aG3HUyYxw/dpsKzX6IWpeOmyezfmJ+IJ6TT+1PPz4w3ffNR7U9xfNHLpjEtG7ZLItyQJWAnQib9Sbz0kMK7UxKCFzmrT9nEjhGta3wM3Mobv4nvWDC4b/o8c//fiUU74khhex4VhhSCw2q/Y2tV9aBu52u6wuLEctLCvP834Q1DUtl6tVVcWjBRqu2Ag+Q6ldxMjw9NgZebAjRj2Zury+BlGld3xtbEl4wm+9ncKl+7plRCBX4ZSL76j0X2f4YdYhvtj81xvgzWiIr9qHbgQMQS27gQc1LwVQ9BWBuP80ihslpdBVtcwrhRiM90og3joiWET39Mdv7zUZDpbjuPf3i7UDb3eCP6VhlSyjLgiMpDYSrwQiByCvKXJkA1Oxket1zETVRqAchGC/wvXtIwI9Jp7mM8bE3IlVri6KvA8aIqrVcZlTgxDyDkRmD4hDoBMVlVVEDVlFYYHSJ0RkQOBohfDaNoQVA5YJajha885Wmu4m1vSjKzZxT599/1PTI+798xvKg2scIftLvHmorg2PJ3R2YVtIag5s1ua8DMVXOTA35MJ33qpvq/z4jaxyGbFRA8RM//z633/+/qsLWi11nx+jGqJB/Rr9hjaKxCEh5aZxtcZm0d8WIqabrT1jXhMrWsPyKFUp8XAzsxH/SkQA7ctLc+i+OOeU+8NAiYj1egBhptcdCMu6LiHs1DrxnY1ajyHkal0lF+ns58tNBMDd5+1OkHRg019v0+5+lAiPTmGjiQAL0ryMDOl4eRKLqmw1u5IN6lDItdsTwYafnmkQzTJs4QtDef6cS3t/u000NETIYTgmwg/Dijz4YagTTy0M+ySIDENCihGGAoSuEybbE8FTIq6bW8t31ayXVdayK+Ln1ag31gV0+drx1WvXw4HPn7u3bv/Y09gIwCmcu3brM9sq2mwz+VVPDaFJHoPp2cFsbh5eunarxgVIorgbHgezO1oiMlUlN1yqKjEWE1UlZsJQ1R6EQ10dU/moarUTET2XU4o17wnpgkmlewuw8Vz14ja/Lpw0CTNhuHStu00xXaVz+W7dRuMtERqdE0+rzDkzEDJL9Qpsdg4NKw1mJ3Ygok9102qnT4fTMR6tWaV7C3gGbJdRcZV2H14q8/rKtb3N7ZO/cW9qyCoyW+zs8LZERGFI3KSAmQmVmYkxMxOlRs0EHDqhsBMRdFAFXDl7vAcbn8btxCXXjBl2i2bnB9I7hr3xpN2IHOp4tHBt2l6bbrrFcG3TZ0CuZAydnVefOJGNoEt1r9QPbHis69YJLRDzYT5sNj9mkh/IGj0rJirjxe2wn66eiOxaYi3o6007QvRucJ8pYLVPgJ+WO+a4KBHlKBsS05BlxEwYWUZOFVlGjEWajYixcLMRnVmYjUY7EEE84ZWLuEnNTrJ+O5ubSJ3uacmmGcM+PzsbUk2VMnZKbfnaTfuf0hbcMw17vgqrndgSGqDYjYmlOCJncUTEzITA4gifxRFo1ziC/AlV9VcGsiC2k6y6MKkeIQs2PEj2fKY9EjPI6IHx0rURY+K6AEFkLZxtjajLmBFRADzciYnt4whnhzgCNAtCKJfXR6eb67pj1I5caWSMcrYfuGxPpc3eFktmsrPFJbp53qYdzb1m6QFEt/OA++62cDgWiABgJ+10IhtBN2VxqRleZoLu1Zf6RLjI75dGz2KSp/lrV20ljqyhzpiggwUVRVsmgkfUbqwPElCP/dUZcnRrMCXChJ1JZ7BLludkRACPWmB3STuxFFRNH30kwcFIgTnlhE6ChK3EkUa6I7uAOT/1JR4a1tb6RGbKOtf6qLoJE/mllCzGGIn4SAHglAhAly/xqh3GEDdEGGVJfMeipA7lsCzpMpXlFHQGaVnSfGC5ExHNunIKVOfPp0ylGDbCDRGWGpl36EDhqcTL1G2I6NJrnctE8DzpVO5q1WP32ZSh9SOopcKogJmDvjWbEoSBXZR6KJuT5sSh2VpraRZqsDMRJIyN6RILJNqi4+IiuKBmyTM6pPY6JT7pTkSAbuOVurXTepwkzFNcr5WoT0xSQgTtDWk6xG4VE8wbdkikvXDtQpfI3JVGAvtWE4SvL43aJMLsCPqwG5UdHcSxjt1eQs7aWNLNEc7ivjdZMThgJxAi/KgdFRKCemciBISIcyoju6LbGtl9qh+mqwYRG50i5EOO97jdiACzOI0rVUsQhIwmPlodFBIHoEtEjkzipsIAtSfzpCWCJiqG4lUiKnLeEJYR6aNhE+8p18wooAuf11YSAKuPOIeLoEd9CVvh+oJuZkkRQcc9dFo1JaJZZ7zWtT2IOIWNoBA7051D2eIf9IhrJep1ow6TP+sRekPPoIeElggdUqt7lYiYcHulvjvLgKTXOK5YSUSoCRXOI1vxOU3DdHVAm9DTVc2RY/gaFicHMrGsml4eIsg9DhfmcrHIwG8efoRsjXQ1Kn1CRMbsggCLjqGk9AViEaHfeLrMp239WuqMDblVUKCbNzpQWi1OT60EwKtdIbF1IKl9TAdb2CQ+dGSxDyLV8tR6VWlV3n6QHiEibJfgV5OXigiAIxqdNyOrGREyk6cQel4OJ9RrGtNsqchcoriqRq5BfaXGPYrIkZh3kR84yAkILVRF0pj7CkiPM9pdsYTiGENoFtCHxrblDUKEyRaTIdhNNRWbRX8YEYAuPFlN2CppLGtXNqqefRg11kiaipynkxOIjcD00KRhSIcxAvkcZvaIKjKqsWit4zKMce43Ho9Al7k7NhEr1wZfhf1VU68wdsO+003p8oG4ctsYGvlynsuN5qGZWqUwp0Y86NIju4m3LcSLloTMPukRfR+x6EJJkb2MmdeJpaaHH58ICAfbKCiqmtpVl/q7qabzgsnRTeyFFAcyC5bM6PHT3B7jQWozUIK9YCOQZ7jXrX8vTRXtcYnI2081NvcKQoTXqibZf4mJYFlwhXrLUyfIdlKX7UXmGv4seqOZQKXNyUoL14Y0clbS1VEXFub6s8bNCp2iyKODQUKaGTZRYS0F/bsEdGcGYqKEldbepBlQw8EyEy5nie1ZZ9xsQMEi8zhsz3osclZWp1Zxd74E6ilRXD82xVLpyP8W4fjlJaLZ5YEY21E/kuQ85po0SMZCDFhUlixFQdnUhQrBbSpDvebatLl2VaLJlnd2OvanQrqmMpXES3iZR/SEitvUpCkaP4rINmji4vYsK9oNPaBduXY1DyA8Hw8Qdl5m8e4Avre0XIcCh/TGEvfSaMmYWgKUXbo2XScErXcmGk6+cJAH5qng5MrtasccsCWU04XGSBdI5aanoxxOB9QoEGbT+cxJZ+FaLrpGKzjZXFqZNJuJJR+M7sIHx6ev/UGURUD0gAmwqEY0G+YT6fh0Ij1PQrKD5q1cgaM36SK3WlC4SG7v2AjCpWsbM+zG1ylninC6+OYRdjxbxNR9Pc/EXq4KgNTrdbNE1oNBqfJK1gFBZeB0IFWdwXE9cwKbN8WrgkWiyV/1TvHKa1fAbxXUKQI6ONo85pM8yPuv99DC7dWgGse6Vo3NuosM0geUUI0KvvABtIUbXttua4TxiYjYagrcGKKwB8TEBo7v7KnQoViEue5oYFICPY56mpG4jhu6fOqBQlZvCxGEitEJiBhvp5TiWtViMa07ANYdKRkFe4gtwF6O5doEagQEOeCBU3sgkiU7R0AMhJta9Hwf+OVxH5ugt626ybwyUAUdpDy0o35dVgesPKxvGkl3G3DcgX7bC6Qn+rDyiqggvo8VCKNDnl/x9sx2evkg2EBIgBaJQMZaCJLo1s0OuMMdXioItiQv9iKRxm/2dKsujcVH2tm2f/33RajaMHJNLAkAdQWMBXlChxHX1QQkjoSTTDOBpO27VuMdtobq2FCY8GpdSbw1keSsT4Se9ABQzEEeR2EsjE0DpLduOtTJkIiStbRrQ2fJs0JEdPN8DInNurxNs8Zh0OzJCcw1YUlm2m5dgYneF/pBLKsOGpDGCBmuWfJSP8xAGUugPDR4/5eBXeKiO46AHNg4JyGXbNEViyXdAVY3wDi3BkAsgUACMUsKQVe3oaSNncRKcgf2yXW8vWYB0iq0Ieg4QRV5cd2xpIlKJ80N1awHDFEOnB6IoA2Gd0aihWCBQV2GctUdYytWw6FA98UVAs5Wuqolj2QD5EloCByCtQj4gVOpkSC7glBpBp+USQGy1QPWEx2EAGlAc7AdIhFoIttBLSQdSMO8h3wgVUDcsLf7vxEsCQysDqg7aj/K5EpQgWEDz00KNOS7/UDGAwCxrAPOYzsNd1Szl/FyDZKKL4FcqDVQ16TTN40UkUseaHfByRRCDlLP0rVOLnXLquKh6lIighQpRIGEaTVJyIM7HI9tRkQAgZ6CSAfC2OZqb5BbYHRzUzj+lWB3sI9xCPjQBprtAU+k5tMURUwUiAhM3hMRXUcQN7aZaBTeBOQNRC41AQoROny98jtQOAeaS/9Ou9zhDpfx/1zTpclwU4wjAAAAAElFTkSuQmCC" alt="redirection logo"></p>
In this project, I learned about using the `head`, `tail`, `find`, `wc`, `sort`,
`uniq`, `grep`, and `tr` commands to redirect standard input and output and
combine commands in the Shell. Further, I learned about how special characters
work and how to filter text from files.

## Tasks :page_with_curl:

* **0. Hello World**
  * [0-hello_world](./0-hello_world): Bash script that prints "Hello, World"
  followed by a new line to the standard output.

* **1. Confused smiley**
  * [1-confused_smiley](./1-confused_smiley): Bash script that displays a confused smiley
  `"(Ôo)'`.

* **2. Let's display a file**
  * [2-hellofile](./2-hellofile): Bash script that displays the content of the
  `/etc/passwd` file.

* **3. What about 2?**
  * [3-twofiles](./3-twofiles): Bash script that displays the content of
  `etc/passwd` and `/etc/hosts`.

* **4. Last lines of a file**
  * [4-lastlines](./4-lastlines): Bash script that displays the last 10 lines of `/etc/passwd`.

* **5. I'd prefer the first ones actually**
  * [5-firstlines](./5-firstlines): Bash script that displays the first 10 lines
  of `/etc/passwd`.

* **6. Line #2**
  * [6-third_line](./6-third_line): Bash script that displays the third line
  of the file `iacta`.

* **7. It is a good file that cuts iron without making a noise**
  * [7-file](./7-file): Bash script that creates a file named exactly
  `\*\\'"Holberton School"\'\\*$\?\*\*\*\*\*:)` containing the text
  `Holberton School` ending by a new line.

* **8. Save current state of directory**
  * [8-cwd_state](./8-cwd_state): Bash script that writes into the file `ls_cwd_content` the
  result of the command `ls -la`.

* **9. Duplicate last line**
  * [9-duplicate_last_line](./9-duplicate_last_line): Bash script that duplicates the last
  line of the file `iacta`.

* **10. No more javascript**
  * [10-no_more_js](./10-no_more_js): Bash script that deletes all the regular files (not
  directories) with a `.js` extension that are present in the current directory
  and all its subfolders.

* **11. Don't just count your directories, make your directories count**
  * [11-directories](./11-directories): Bash script that counts the number of directories and
  sub-directories in the current directory, not including the current and parent
  directories but counting hidden ones.

* **12. What’s new**
  * [12-newest_file](./12-newest_files): Bash script that displays the 10 newest files in the
  current directory, one file per line, sorted from newest to oldest.

* **13. Being unique is better than being perfect**
  * [13-unique](./13-unique): Bash script that takes a list of words as input and only
  prints words that appear exactly once, one word per line, sorted.

* **14. It must be in that file**
  * [14-findthatword](./14-findthatword): Bash script that displays lines containing
  the pattern "root" from the file `/etc/passwd`.

* **15. Count that word**
  * [15-countthatword](./15-countthatword): Bash script that displays the number of lines
  containing the pattern "bin" in the file `/etc/passwd`.

* **16. What's next?**
  * [16-whatsnext](./16-whatsnext): Bash script that displays lines containing the pattern
  "root" and 3 lines after them in the file `/etc/passwd`.

* **17. I hate bins**
  * [17-hidethisword](./17-hidethisword): Bash script that displays all lines in the file
  `/etc/passwd` that do not contain the pattern "bin".

* **18. Letters only please**
  * [18-letteronly](./18-letteronly): Bash script that displays all lines of the file
  `/etc/ssh/sshd_config` starting with a letter, including capital letters.

* **19. A to Z**
  * [19-AZ](./19-AZ): Bash script that replaces all characters `A` and `c` from input
  to `Z` and `e` respectively.

* **20. Without C, you would live in hiago**
  * [20-hiago](./20-hiago): Bash script that removes all letters `c` and `C` from input.

* **21. esreveR**
  * [21-reverse](./21-reverse): Bash script that reverses its input.

* **22. DJ Cut Killer**
  * [22-users_and_homes](./22-users_and_homes): Bash script that displays all users and
  their home directories, sorted by users, based on the `/etc/passwd` file.

* **23. Empty casks make the most noise**
  * [100-empty_casks](./100-empty_casks): Bash script that finds all empty files
  and directories in the current directory and all sub-directories as follows:
    * Only the names of the files and directories are displayed.
    * Hidden files included.
    * One file name per line.

* **24. A gif is worth ten thousand words**
  * [101-gifs](./101-gifs): Bash script that lists all the files with a `.gif` extension
  in the current directory and all its sub-directories as follows:
    * Hidden files included.
    * Only regular files (not directories) listed.
    * File names displayed without extensions.
    * Files sorted by byte values, but case insensitive.
    * One file name per line.

* **25. Acrostic**
  * [102-acrostic](./102-acrostic): Bash script that decodes acrostics that use the first
  letter of each line.

* **26. The biggest fan**
  * [103-the_biggest_fan](./103-the_biggest_fan): Bash script that parses web
  server logs in TSV format as input and displays the 11 hosts or IP addresses
  which did the most requests.
  * Ordered by number of requests, with most active hosts or IP's at the top.