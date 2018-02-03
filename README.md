# jQueryStefCode Part II.js
Apa Itu jQueryStefCode Part II.js sebuah plugin jquery yang sederhana untuk mendeteksi user menekan tombol keyboard sesuai pilihan cara penggunaan.<br>

<br>
<br>
Plugin ini di buat oleh Stefanus Prasetyo Nugroho.

## Instalasi
Untuk bisa memakai plugin ini anda membutuhkan jquery terlebih dahulu bebas versi berapa aja<br>


anda  bisa menggunakan seperti ini menggunakan tag script biasa, contoh:


```javascript
<script
  src="http://code.jquery.com/jquery-3.3.1.min.js"
  integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
  crossorigin="anonymous"></script>

<script src="asset/js/jQueryStefCodePartII.js"></script>
```

Anda Bisa mendapatkan jQueryStefPlaySound.JS berikut:<br>
<code>https://raw.githubusercontent.com/stefanuspn/StefPlaySound/master/asset/js/jQueryStefCodePartII.js</code>

### Cara Menggunakan
Siapkan terlebih dahulu file-file yang sudah disebutkan diatas yaitu jquery-3.2.1.min.js dan jQueryStefCodePartII.js :<br>

```html


<script>
  src="http://code.jquery.com/jquery-3.3.1.min.js"
  integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
  crossorigin="anonymous"></script>

<script src="asset/js/jQueryStefCodePartII.js"></script>

<script>
$(document).ready(function(){
   $(window).stefcode2({
      code : 65 , // menekan fungsi keyboard
       callback: function() {
          swal('Oops!', 'Sorry Gan tombol a Gak Bisa hehe!.', 'error'); setTimeout(1000);
            }
       });
});

$(document).ready(function(){
   $(window).stefcode2({
      ctrlcode : 85 , // menekan fungsi keyboard ctrl+
       callback: function() {
          $(".coba").html("hai");
            }
       });
});

$(document).ready(function(){
   $(window).stefcode2({
      alt : 83 , // menekan fungsi keyboard alt+
       callback: function() {
          $(".coba").html("hai");
            }
       });
});
</script>
```
 <p style="text-align: justify;">Berikut ini adalah kode lengkap untuk masing-masing tombol</p>
    <table>
        <tbody>
            <tr>
                <td>
                    <table>
                        <tbody>
                            <tr>
                                <td>Key</td>
                                <td>Code</td>
                            </tr>
                            <tr>
                                <td>backspace</td>
                                <td>8</td>
                            </tr>
                            <tr>
                                <td>tab</td>
                                <td>9</td>
                            </tr>
                            <tr>
                                <td>enter</td>
                                <td>13</td>
                            </tr>
                            <tr>
                                <td>shift</td>
                                <td>16</td>
                            </tr>
                            <tr>
                                <td>ctrl</td>
                                <td>17</td>
                            </tr>
                            <tr>
                                <td>alt</td>
                                <td>18</td>
                            </tr>
                            <tr>
                                <td>pause/break</td>
                                <td>19</td>
                            </tr>
                            <tr>
                                <td>caps lock</td>
                                <td>20</td>
                            </tr>
                            <tr>
                                <td>escape</td>
                                <td>27</td>
                            </tr>
                            <tr>
                                <td>(space)</td>
                                <td>32</td>
                            </tr>
                            <tr>
                                <td>page up</td>
                                <td>33</td>
                            </tr>
                            <tr>
                                <td>page down</td>
                                <td>34</td>
                            </tr>
                            <tr>
                                <td>end</td>
                                <td>35</td>
                            </tr>
                            <tr>
                                <td>home</td>
                                <td>36</td>
                            </tr>
                            <tr>
                                <td>left arrow</td>
                                <td>37</td>
                            </tr>
                            <tr>
                                <td>up arrow</td>
                                <td>38</td>
                            </tr>
                            <tr>
                                <td>right arrow</td>
                                <td>39</td>
                            </tr>
                            <tr>
                                <td>down arrow</td>
                                <td>40</td>
                            </tr>
                            <tr>
                                <td>insert</td>
                                <td>45</td>
                            </tr>
                            <tr>
                                <td>delete</td>
                                <td>46</td>
                            </tr>
                            <tr>
                                <td>0</td>
                                <td>48</td>
                            </tr>
                            <tr>
                                <td>1</td>
                                <td>49</td>
                            </tr>
                            <tr>
                                <td>2</td>
                                <td>50</td>
                            </tr>
                            <tr>
                                <td>3</td>
                                <td>51</td>
                            </tr>
                            <tr>
                                <td>4</td>
                                <td>52</td>
                            </tr>
                            <tr>
                                <td>5</td>
                                <td>53</td>
                            </tr>
                            <tr>
                                <td>6</td>
                                <td>54</td>
                            </tr>
                            <tr>
                                <td>7</td>
                                <td>55</td>
                            </tr>
                            <tr>
                                <td>8</td>
                                <td>56</td>
                            </tr>
                            <tr>
                                <td>9</td>
                                <td>57</td>
                            </tr>
                            <tr>
                                <td>a</td>
                                <td>65</td>
                            </tr>
                            <tr>
                                <td>b</td>
                                <td>66</td>
                            </tr>
                            <tr>
                                <td>c</td>
                                <td>67</td>
                            </tr>
                            <tr>
                                <td>d</td>
                                <td>68</td>
                            </tr>
                        </tbody>
                    </table>
                </td>
                <td>&nbsp;</td>
                <td>
                    <table>
                        <tbody>
                            <tr>
                                <td>Key</td>
                                <td>Code</td>
                            </tr>
                            <tr>
                                <td>e</td>
                                <td>69</td>
                            </tr>
                            <tr>
                                <td>f</td>
                                <td>70</td>
                            </tr>
                            <tr>
                                <td>g</td>
                                <td>71</td>
                            </tr>
                            <tr>
                                <td>h</td>
                                <td>72</td>
                            </tr>
                            <tr>
                                <td>i</td>
                                <td>73</td>
                            </tr>
                            <tr>
                                <td>j</td>
                                <td>74</td>
                            </tr>
                            <tr>
                                <td>k</td>
                                <td>75</td>
                            </tr>
                            <tr>
                                <td>l</td>
                                <td>76</td>
                            </tr>
                            <tr>
                                <td>m</td>
                                <td>77</td>
                            </tr>
                            <tr>
                                <td>n</td>
                                <td>78</td>
                            </tr>
                            <tr>
                                <td>o</td>
                                <td>79</td>
                            </tr>
                            <tr>
                                <td>p</td>
                                <td>80</td>
                            </tr>
                            <tr>
                                <td>q</td>
                                <td>81</td>
                            </tr>
                            <tr>
                                <td>r</td>
                                <td>82</td>
                            </tr>
                            <tr>
                                <td>s</td>
                                <td>83</td>
                            </tr>
                            <tr>
                                <td>t</td>
                                <td>84</td>
                            </tr>
                            <tr>
                                <td>u</td>
                                <td>85</td>
                            </tr>
                            <tr>
                                <td>v</td>
                                <td>86</td>
                            </tr>
                            <tr>
                                <td>w</td>
                                <td>87</td>
                            </tr>
                            <tr>
                                <td>x</td>
                                <td>88</td>
                            </tr>
                            <tr>
                                <td>y</td>
                                <td>89</td>
                            </tr>
                            <tr>
                                <td>z</td>
                                <td>90</td>
                            </tr>
                            <tr>
                                <td>left window key</td>
                                <td>91</td>
                            </tr>
                            <tr>
                                <td>right window key</td>
                                <td>92</td>
                            </tr>
                            <tr>
                                <td>select key</td>
                                <td>93</td>
                            </tr>
                            <tr>
                                <td>numpad 0</td>
                                <td>96</td>
                            </tr>
                            <tr>
                                <td>numpad 1</td>
                                <td>97</td>
                            </tr>
                            <tr>
                                <td>numpad 2</td>
                                <td>98</td>
                            </tr>
                            <tr>
                                <td>numpad 3</td>
                                <td>99</td>
                            </tr>
                            <tr>
                                <td>numpad 4</td>
                                <td>100</td>
                            </tr>
                            <tr>
                                <td>numpad 5</td>
                                <td>101</td>
                            </tr>
                            <tr>
                                <td>numpad 6</td>
                                <td>102</td>
                            </tr>
                            <tr>
                                <td>numpad 7</td>
                                <td>103</td>
                            </tr>
                        </tbody>
                    </table>
                </td>
                <td>&nbsp;</td>
                <td>
                    <table>
                        <tbody>
                            <tr>
                                <td>Key</td>
                                <td>Code</td>
                            </tr>
                            <tr>
                                <td>numpad 8</td>
                                <td>104</td>
                            </tr>
                            <tr>
                                <td>numpad 9</td>
                                <td>105</td>
                            </tr>
                            <tr>
                                <td>multiply</td>
                                <td>106</td>
                            </tr>
                            <tr>
                                <td>add</td>
                                <td>107</td>
                            </tr>
                            <tr>
                                <td>subtract</td>
                                <td>109</td>
                            </tr>
                            <tr>
                                <td>decimal point</td>
                                <td>110</td>
                            </tr>
                            <tr>
                                <td>divide</td>
                                <td>111</td>
                            </tr>
                            <tr>
                                <td>f1</td>
                                <td>112</td>
                            </tr>
                            <tr>
                                <td>f2</td>
                                <td>113</td>
                            </tr>
                            <tr>
                                <td>f3</td>
                                <td>114</td>
                            </tr>
                            <tr>
                                <td>f4</td>
                                <td>115</td>
                            </tr>
                            <tr>
                                <td>f5</td>
                                <td>116</td>
                            </tr>
                            <tr>
                                <td>f6</td>
                                <td>117</td>
                            </tr>
                            <tr>
                                <td>f7</td>
                                <td>118</td>
                            </tr>
                            <tr>
                                <td>f8</td>
                                <td>119</td>
                            </tr>
                            <tr>
                                <td>f9</td>
                                <td>120</td>
                            </tr>
                            <tr>
                                <td>f10</td>
                                <td>121</td>
                            </tr>
                            <tr>
                                <td>f11</td>
                                <td>122</td>
                            </tr>
                            <tr>
                                <td>f12</td>
                                <td>123</td>
                            </tr>
                            <tr>
                                <td>num lock</td>
                                <td>144</td>
                            </tr>
                            <tr>
                                <td>scroll lock</td>
                                <td>145</td>
                            </tr>
                            <tr>
                                <td>semi-colon</td>
                                <td>186</td>
                            </tr>
                            <tr>
                                <td>equal sign</td>
                                <td>187</td>
                            </tr>
                            <tr>
                                <td>comma</td>
                                <td>188</td>
                            </tr>
                            <tr>
                                <td>dash</td>
                                <td>189</td>
                            </tr>
                            <tr>
                                <td>period</td>
                                <td>190</td>
                            </tr>
                            <tr>
                                <td>forward slash</td>
                                <td>191</td>
                            </tr>
                            <tr>
                                <td>grave accent</td>
                                <td>192</td>
                            </tr>
                            <tr>
                                <td>open bracket</td>
                                <td>219</td>
                            </tr>
                            <tr>
                                <td>back slash</td>
                                <td>220</td>
                            </tr>
                            <tr>
                                <td>close braket</td>
                                <td>221</td>
                            </tr>
                            <tr>
                                <td>single quote</td>
                                <td>2</td>
                            </tr>
                        </tbody>
                    </table>
                </td>
            </tr>
        </tbody>
    </table>
    <p style="text-align: justify;">Silahkan dicoba, jangan lupa dilike dan dishare ya.. Terima kasih telah berkunjung ke harviacode.com.</p>
    <p>&nbsp;</p>
