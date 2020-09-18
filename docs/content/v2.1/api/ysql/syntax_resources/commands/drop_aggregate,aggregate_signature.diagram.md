#### drop_aggregate

<svg class="rrdiagram" version="1.1" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg" width="866" height="100" viewbox="0 0 866 100"><path class="connector" d="M0 52h15m53 0h10m94 0h30m32 0h10m64 0h20m-141 0q5 0 5 5v8q0 5 5 5h116q5 0 5-5v-8q0-5 5-5m5 0h30m-5 0q-5 0-5-5v-20q0-5 5-5h165m24 0h165q5 0 5 5v20q0 5-5 5m-228 0h10m25 0h10m143 0h10m25 0h50m77 0h22m-109 25q0 5 5 5h5m79 0h5q5 0 5-5m-104-25q5 0 5 5v33q0 5 5 5h89q5 0 5-5v-33q0-5 5-5m5 0h15"/><polygon points="0,59 5,52 0,45" style="fill:black;stroke-width:0"/><rect class="literal" x="15" y="35" width="53" height="25" rx="7"/><text class="text" x="25" y="52">DROP</text><rect class="literal" x="78" y="35" width="94" height="25" rx="7"/><text class="text" x="88" y="52">AGGREGATE</text><rect class="literal" x="202" y="35" width="32" height="25" rx="7"/><text class="text" x="212" y="52">IF</text><rect class="literal" x="244" y="35" width="64" height="25" rx="7"/><text class="text" x="254" y="52">EXISTS</text><rect class="literal" x="518" y="5" width="24" height="25" rx="7"/><text class="text" x="528" y="22">,</text><a xlink:href="../../syntax_resources/grammar_diagrams#aggregate-name"><rect class="rule" x="358" y="35" width="121" height="25"/><text class="text" x="368" y="52">aggregate_name</text></a><rect class="literal" x="489" y="35" width="25" height="25" rx="7"/><text class="text" x="499" y="52">(</text><a xlink:href="#aggregate-signature"><rect class="rule" x="524" y="35" width="143" height="25"/><text class="text" x="534" y="52">aggregate_signature</text></a><rect class="literal" x="677" y="35" width="25" height="25" rx="7"/><text class="text" x="687" y="52">)</text><rect class="literal" x="752" y="35" width="77" height="25" rx="7"/><text class="text" x="762" y="52">CASCADE</text><rect class="literal" x="752" y="65" width="79" height="25" rx="7"/><text class="text" x="762" y="82">RESTRICT</text><polygon points="862,59 866,59 866,45 862,45" style="fill:black;stroke-width:0"/></svg>

#### aggregate_signature

<svg class="rrdiagram" version="1.1" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg" width="529" height="170" viewbox="0 0 529 170"><path class="connector" d="M0 22h35m28 0h451m-489 55q0 5 5 5h25m-5 0q-5 0-5-5v-20q0-5 5-5h46m24 0h46q5 0 5 5v20q0 5-5 5m-5 0h338q5 0 5-5m-484-55q5 0 5 5v110q0 5 5 5h45m-5 0q-5 0-5-5v-20q0-5 5-5h46m24 0h46q5 0 5 5v20q0 5-5 5m-5 0h40m-181 0q5 0 5 5v8q0 5 5 5h156q5 0 5-5v-8q0-5 5-5m5 0h10m62 0h10m35 0h30m-5 0q-5 0-5-5v-20q0-5 5-5h46m24 0h46q5 0 5 5v20q0 5-5 5m-5 0h25q5 0 5-5v-110q0-5 5-5m5 0h15"/><polygon points="0,29 5,22 0,15" style="fill:black;stroke-width:0"/><rect class="literal" x="35" y="5" width="28" height="25" rx="7"/><text class="text" x="45" y="22">*</text><rect class="literal" x="96" y="35" width="24" height="25" rx="7"/><text class="text" x="106" y="52">,</text><a xlink:href="../../syntax_resources/grammar_diagrams#aggregate-arg"><rect class="rule" x="55" y="65" width="106" height="25"/><text class="text" x="65" y="82">aggregate_arg</text></a><rect class="literal" x="116" y="95" width="24" height="25" rx="7"/><text class="text" x="126" y="112">,</text><a xlink:href="../../syntax_resources/grammar_diagrams#aggregate-arg"><rect class="rule" x="75" y="125" width="106" height="25"/><text class="text" x="85" y="142">aggregate_arg</text></a><rect class="literal" x="231" y="125" width="62" height="25" rx="7"/><text class="text" x="241" y="142">ORDER</text><rect class="literal" x="303" y="125" width="35" height="25" rx="7"/><text class="text" x="313" y="142">BY</text><rect class="literal" x="409" y="95" width="24" height="25" rx="7"/><text class="text" x="419" y="112">,</text><a xlink:href="../../syntax_resources/grammar_diagrams#aggregate-arg"><rect class="rule" x="368" y="125" width="106" height="25"/><text class="text" x="378" y="142">aggregate_arg</text></a><polygon points="525,29 529,29 529,15 525,15" style="fill:black;stroke-width:0"/></svg>
