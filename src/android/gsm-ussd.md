# GSM & USSD Codes

## What are GSM and USSD?

[GSM](https://en.wikipedia.org/wiki/GSM) - [Global System for Mobile Communications](https://el.wikipedia.org/wiki/Global_System_for_Mobile_Communications)

### GSM (Global System for Mobile Communications)

**GSM** is a digital cellular communication standard developed to enable mobile phones to communicate over second-generation (**2G**) networks. It defines the protocols used for voice calls, **SMS** (Short Message Service), and basic mobile data, while also introducing features such as international roaming and interoperability between mobile network operators. Although newer technologies like 4G and 5G are now common, GSM remains the foundation upon which many mobile network services were built.

[USSD](https://en.wikipedia.org/wiki/Unstructured_Supplementary_Service_Data)

### USSD (Unstructured Supplementary Service Data)

**USSD** is a communication protocol used by GSM networks that allows a mobile phone to exchange text-based messages with the carrier's systems in real time. Unlike SMS, USSD establishes a live session between the device and the network, making it ideal for interactive menus and service requests. It does not require an internet connection and is commonly used for tasks such as checking prepaid balances, activating call forwarding, accessing banking services, and retrieving account information. **USSD** codes typically begin with **`*`** and end with **`#`**, for example **`*#06#`** to display a device's IMEI number (supported on most phones).

<!-- Example 

<tr>
<td> <b>  </b> </td>
<td>  </td>
</tr>

-->

---

### Call Forwarding

<table>

<th>Code</th> <th>Functionallity</th> <th>Example</th>

<!-- 1 -->

<tr>
<td> <b> **21*(number)# </b> </td> 
<td> Activate unconditional forwarding (all calls) </td> 
<td> **21*001234567890# </td>
</tr>

<!-- 2 -->

<tr>
<td> <b> ##21# </b> </td>
<td> De-Activate unconditional forwarding </td>
<td> </td>
</tr>

<!-- 3 -->

<tr>
<td> <b> *#21# </b> </td> 
<td> Check unconditional forwarding status </td>
<td> </td>
</tr>

<!-- 4 -->

<tr>
<td> <b> **61*(number)**(seconds)# </b> </td>
<td> Forward when no answer (set ring time in seconds: 5-20) </td>
<td> **61*001234567890**20# </td>
</tr>

<!-- 5 -->

<tr>
<td> <b> ##61# </b> </td>
<td> Deactivate no-answer forwarding </td>
<td> </td>
</tr>

<!-- 5 -->

<tr>
<td> <b> *#61# </b> </td>
<td> Check no-answer forwarding status </td>
<td> </td>
</tr>

<!-- 6 -->

<tr>
<td> <b> **67*(number)# </b> </td>
<td> Forward when busy </td>
<td> **67*001234567890# </td>
</tr>

<!-- 7 -->

<tr>
<td> <b> ##67# </b> </td>
<td> Deactivate busy forwarding </td>
<td> </td>
</tr>

<!-- 8 -->

<tr>
<td> <b> *#67# </b> </td>
<td> Check busy forwarding status </td>
<td> </td>
</tr>

<!-- 9 -->

<tr>
<td> <b> **62*(number)# </b> </td>
<td> Forward when unreachable (if the phone is off or has no signal) </td>
<td> **62*001234567890# </td>
</tr>

<!-- 10 -->

<tr>
<td> <b> ##62# </b> </td>
<td> Deactivate unreachable forwarding </td>
<td> </td>
</tr>

<!-- 11 -->

<tr>
<td> <b> *#62# </b> </td>
<td> Check unreachable forwarding status </td>
<td> </td>

</tr>

<!-- 12 -->

<tr>
<td> <b> ##002# </b> </td>
<td> Cancel all forwarding rules at once </td>
<td> </td>
</tr>

<!-- 13 -->

<tr>
<td> <b> ##004# </b> </td>
<td> Cancel all conditional forwarding (no answer & busy & unreachable) </td>
<td> </td>
</tr>

</table>

### Call Waiting

<table>

<th>Code</th> <th>Functionallity</th>

<!-- 1 -->

<tr>
<td> <b> *43# </b> </td>
<td> Activate call waiting </td>
</tr>

<!-- 2 -->

<tr>
<td> <b> #43# </b> </td>
<td> Deactivate call waiting </td>
</tr>

<!-- 3 -->

<tr>
<td> <b> *#43# </b> </td>
<td> Check call waiting status </td>
</tr>

</table>

### Caller ID - CLIR

<table>

<th>Code</th> <th>Functionallity</th> <th>Example</th>

<!-- 1 -->

<tr>
<td> <b> #31#(number) </b> </td>
<td> Hide your number for the next call only </td>
<td> #31#001234567890 </td>
</tr>

<!-- 2 -->

<tr>
<td> <b> *31#(number) </b> </td>
<td> Show your number for the next call (if normally hidden) </td>
<td> *31#001234567890 </td>
</tr>

<!-- 3 -->

<tr>
<td> <b> *#31# </b> </td>
<td> Check your caller ID (CLIR) status </td>
<td> </td>
</tr>

<!-- 4 -->

<tr>
<td> <b> *#30# </b> </td>
<td> Check incoming caller ID (CLIP) status </td>
<td> </td>
</tr>

<!-- 5 -->

<tr>
<td> <b> *#76# </b> </td>
<td> Check connected line presentation (COLP) status </td>
<td> </td>
</tr>

<!-- 6 -->

<tr>
<td> <b> *#77# </b> </td>
<td> Check connected line restriction (COLR) status </td>
<td> </td>
</tr>

</table>

### Call Barring

<table>

<th>Code</th> <th>Functionallity</th> <th>Example</th>

<!-- 1 -->

<tr>
<td> <b> **33*(PIN)# </b> </td>
<td> 	Bar all outgoing calls <p style="color:#fefefe">(Note: <b style="color:white">PIN</b> is your call barring password (default is often <b style="color:white">0000</b> or <b style="color:white">1234</b>, set by carrier)</p> </td>
<td> **33*0000# </td>
</tr>

<!-- 2 -->

<tr>
<td> <b> ##33*(PIN)# </b> </td>
<td> Remove outgoing call bar </td>
<td> ##33*0000# </td>
</tr>

<!-- 3 -->

<tr>
<td> <b> *#33# </b> </td>
<td> Check outgoing call bar status </td>
<td> <td>
</tr>

<!-- 4 -->

<tr>
<td> <b> **331*(PIN)# </b> </td>
<td> Bar all outgoing international calls </td>
<td> **331*0000# </td>
</tr>

<!-- 5 -->

<tr>
<td> <b> ##331*(PIN)# </b> </td>
<td> Remove international call bar </td>
<td> ##331*0000# </td>
</tr>

<!-- 6 -->

<tr>
<td> <b> **35*(PIN)# </b> </td>
<td> Bar all incoming calls </td>
<td> **35*0000# </td>
</tr>

<!-- 7 -->

<tr>
<td> <b> ##35*(PIN)# </b> </td>
<td> Remove incoming call bar </td>
<td> ##35*0000# </td>
</tr>

<!-- 8 -->

<tr>
<td> <b> *#35# </b> </td>
<td> Check incoming call bar status </td>
<td> </td>
</tr>

<!-- 9 -->

<tr>
<td> <b> **351*(PIN)# </b> </td>
<td> Bar incoming calls when roaming </td>
<td> **351*0000# </td>
</tr>

<!-- 10 -->

<tr>
<td> <b> ##330*(PIN)# </b> </td>
<td> Remove all call barring </td>
<td> ##330*0000# </td>
</tr>

</table>

### Phone & SIM Info

<table>

<th>Code</th> <th>Functionallity</th>

<!-- 1 -->

<tr>
<td> <b> *#06# </b> </td>
<td> Show <b>IMEI</b> number (device identity) <p style="color: #fefefe">(Note: Write this down and keep it safe. Needed if your phone is lost or stolen.)</p> </td>
</tr>

<!-- 2 -->

<tr>
<td> <b> *#07# </b> </td>
<td> Show SAR (radiation) information <p style="color:#fefefe">(Note: GSM-standard code; works on most Android phones and many iPhones. Shows the specific absorption rate.)</p> </td>
</tr>

</table>


### Voicemail

<table>

<th>Code</th> <th>Functionallity</th> <th>Example</th>

<!-- 1 -->

<tr>
<td> <b> **004*(number)# </b> </td>
<td> Set all conditional forwarding to voicemail/number at once <p style="color:#fefefe">(Note: Sets no-answer, busy, and unreachable forwarding in one step)</p> </td>
<td> **004*001234567890 </td>
</tr>

<!-- 2 -->

<tr>
<td> <b> ##004# </b> </td>
<td> Remove all conditional forwarding (clears voicemail forwarding) </td>
<td> </td>
</tr>

</table>

### Network Selection

<table>

<th>Code</th> <th>Functionallity</th>

<!-- 1 -->

<tr>
<td> <b> *#*#4636#*#* </b> </td>
<td> Phone info and network details (Android only) <p style="color:#fefefe">(Note: Opens a hidden Android menu with battery, network, and usage stats)</p> </td>
</tr>

<!-- 2 -->

<tr>
<td> <b> *#*#7780#*#* </b> </td>
<td> Reset settings/user data (Android only, use with caution) <p style="color:#fefefe">(Note: Resets settings and user data but keeps the installed firmware, not a full factory wipe. Blocked on many recent phones (e.g. Samsung One UI 6.1+))</p> </td>
</tr>

</table>
