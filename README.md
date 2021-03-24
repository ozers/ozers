### Hi there 👋

- 🔭 I’m currently working on development x-platform application
- 🌱 I’m currently learning AWS technologies
- 💬 Ask me about Software Testing and Backend Development
- 📫 How to reach me: ozer.subasi@gmail.com
- ⚡ Fun fact: Asgardians aren't technically immortal.

<!--
**ozers/ozers** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 😄 Pronouns: ...
-->

<html>
<style>
    label {
        display: inline-block;
        text-align: right;
        float: left;
    }

    input {
        display: inline-block;
        text-align: left;
        float: right;
    }
</style>
<table>
    <tr>
        <td>
            <label>Ana Tutar: </label><input type='text' id='anaTutar'>
        </td>
    </tr>
    <tr>
        <td>
            <input type="radio" id="tutar" name="discountType" value="indirimliTutar"><label
                for="indirimliTutar">Indirimli Tutarla Hesapla</label><br>
            <input type="radio" id="yuzde" name="discountType" value="indirimYuzdesi"><label
                for="indirimYuzdesi">Indirim Yuzdesiyle Hesapla</label><br>
        </td>
    </tr>
    <tr>
        <td>
            <label>Indirimli Tutar: </label><input type='text' disabled id='indirimliTutar'>
        </td>
    </tr>
    <tr>
        <td>
            <label>Indirim Yuzdesi: </label><input type='text' disabled id='indirimYuzdesi'>
        </td>
    </tr>
    <tr>
        <td>
            <label>Kac Kisi: </label><input type='text' id='kacKisi'>
        </td>
    </tr>
    <tr>
        <td>
            <input type='submit' value='Hesapla' onClick="hesapla();">
        </td>
    </tr>
    <tr>
        <td>
            <label>Kisi Basi: </label>
            <input type='text' disabled id='kisiBasi'>
        </td>
    </tr>
</table>
