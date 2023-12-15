
## MusER: Musical Element-Based Regularization for Generating Symbolic Music with Emotion
The two-dimensional arousal-valence (A-V) emotion model is widely adopted in the literature, as shown below. Within this model, the two dimensions, namely **arousal** and **valence**, respectively indicate the level of autonomic activation and pleasantness. These two dimensions divide the A-V model into four quadrants, each corresponding to a specific class of emotions. We employ the **four quadrants (4Q)** as the emotion labels for generating emotional music.
<br>
<br>
<img src="https://tayjsl97.github.io/images/VA_model.jpg" width="300" height="150" alt="model"/>
<br>

---

<b><font size=5>Generating music with different emotions (4Q)</font></b>

- Q1

<div style="text-align: left">
<table>
    <tr>
        <td><strong>Example 1</strong></td> 
        <td><strong>Example 2</strong></td> 
        <td><strong>Example 3</strong></td> 
   </tr>
    <tr>
  		<td>
        <div style="width: 17em"></div>
        <div>
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/0-Q1.mp3">
        </audio>
        </div>
        </td> 
        <td>
        <div style="width: 17em"></div>
        <div>
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/1-Q1.mp3">
        </audio>
        </div>
        </td> 
        <td>
        <div style="width: 17em"></div>
        <div>
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/2-Q1.mp3">
        </audio>
        </div>
        </td> 
    </tr>
</table>
</div>

- Q2

<div style="text-align: left">
<table>
    <tr>
        <td><strong>Example 1</strong></td> 
        <td><strong>Example 2</strong></td> 
        <td><strong>Example 3</strong></td> 
   </tr>
    <tr>
  		<td>
        <div style="width: 17em"></div>
        <div>
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/3-Q2.mp3">
        </audio>
        </div>
        </td> 
        <td>
        <div style="width: 17em"></div>
        <div>
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/4-Q2.mp3">
        </audio>
        </div>
        </td> 
        <td>
        <div style="width: 17em"></div>
        <div>
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/5-Q2.mp3">
        </audio>
        </div>
        </td> 
    </tr>
</table>
</div>

- Q3

<div style="text-align: left">
<table>
    <tr>
        <td><strong>Example 1</strong></td> 
        <td><strong>Example 2</strong></td> 
        <td><strong>Example 3</strong></td> 
   </tr>
    <tr>
  		<td>
        <div style="width: 17em"></div>
        <div>
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/6-Q3.mp3">
        </audio>
        </div>
        </td> 
        <td>
        <div style="width: 17em"></div>
        <div>
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/7-Q3.mp3">
        </audio>
        </div>
        </td> 
        <td>
        <div style="width: 17em"></div>
        <div>
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/8-Q3.mp3">
        </audio>
        </div>
        </td> 
    </tr>
</table>
</div>

- Q4

<div style="text-align: left">
<table>
    <tr>
        <td><strong>Example 1</strong></td> 
        <td><strong>Example 2</strong></td> 
        <td><strong>Example 3</strong></td> 
   </tr>
    <tr>
  		<td>
        <div style="width: 17em"></div>
        <div>
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/9-Q4.mp3">
        </audio>
        </div>
        </td> 
        <td>
        <div style="width: 17em"></div>
        <div>
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/10-Q4.mp3">
        </audio>
        </div>
        </td> 
        <td>
        <div style="width: 17em"></div>
        <div>
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/11-Q4.mp3">
        </audio>
        </div>
        </td> 
    </tr>
</table>
</div>

---

<b><font size=5>Musical element transfer</font></b>

- Case 1: Transfer velocity in Q1 to music in Q4 (Q4+Q1 v)

<table>
    <tr>
        <td><strong>Example 1</strong></td> 
        <td> </td>
        <td> </td>
        <td> </td>
    </tr>
    <tr>
  		<td>
        <div style="width: 6em">
        Q4 original: 
        </div>
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/0-Q4_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="width: 7em;text-align: right">
        Q4+Q1 v: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/0-Q4+Q1 velocity.mp3">
        </audio>
        </div>
        </td>
    </tr>
    <tr>
        <td><strong>Example 2</strong></td> 
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
  		<td>
        Q4 original:
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/1-Q4_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="text-align: right">
        Q4+Q1 v: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/1-Q4+Q1 velocity.mp3">
        </audio>
        </div>
        </td>
    </tr>
    <tr>
        <td><strong>Example 3</strong></td> 
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
  		<td>
        <div style="width: 6em">
        Q4 original: 
        </div>
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/2-Q4_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="text-align: right">
        Q4+Q1 v: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/2-Q4+Q1 velocity.mp3">
        </audio>
        </div>
        </td>
    </tr>
</table>

- Case 2: Transfer pitch, duration, and velocity in Q1 to music in Q3 (Q3+Q1 pdv)

<table>
    <tr>
        <td><strong>Example 1</strong></td> 
        <td> </td>
        <td> </td>
        <td> </td>
    </tr>
    <tr>
  		<td>
        <div style="width: 6em">
        Q3 original: 
        </div>
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/3-Q3_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="width: 7em;text-align: right">
        Q3+Q1 pdv: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/3-Q3+Q1 pitch, duration and velocity.mp3">
        </audio>
        </div>
        </td>
    </tr>
    <tr>
        <td><strong>Example 2</strong></td> 
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
  		<td>
        Q3 original:
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/4-Q3_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="text-align: right">
        Q3+Q1 pdv: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/4-Q3+Q1 pitch, duration and velocity.mp3">
        </audio>
        </div>
        </td>
    </tr>
    <tr>
        <td><strong>Example 3</strong></td> 
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
  		<td>
        <div style="width: 6em">
        Q3 original: 
        </div>
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/5-Q3_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="text-align: right">
        Q3+Q1 pdv: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/5-Q3+Q1 pitch, duration and velocity.mp3">
        </audio>
        </div>
        </td>
    </tr>
</table>

- Case 3: Transfer tempo in Q1 to music in Q4 (Q4+Q1 t)

<table>
    <tr>
        <td><strong>Example 1</strong></td> 
        <td> </td>
        <td> </td>
        <td> </td>
    </tr>
    <tr>
  		<td>
        <div style="width: 6em">
        Q4 original: 
        </div>
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/6-Q4_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="width: 7em;text-align: right">
        Q4+Q1 t: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/6-Q4+Q1 tempo.mp3">
        </audio>
        </div>
        </td>
    </tr>
    <tr>
        <td><strong>Example 2</strong></td> 
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
  		<td>
        Q4 original:
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/7-Q4_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="text-align: right">
        Q4+Q1 t: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/7-Q4+Q1 tempo.mp3">
        </audio>
        </div>
        </td>
    </tr>
    <tr>
        <td><strong>Example 3</strong></td> 
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
  		<td>
        <div style="width: 6em">
        Q4 original: 
        </div>
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/8-Q4_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="text-align: right">
        Q4+Q1 t: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/8-Q4+Q1 tempo.mp3">
        </audio>
        </div>
        </td>
    </tr>
</table>

- Case 4: Transfer pitch in Q1 to music in Q3 (Q3+Q1 p)

<table>
    <tr>
        <td><strong>Example 1</strong></td> 
        <td> </td>
        <td> </td>
        <td> </td>
    </tr>
    <tr>
  		<td>
        <div style="width: 6em">
        Q3 original: 
        </div>
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/9-Q3_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="width: 7em;text-align: right">
        Q3+Q1 p: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/9-Q3+Q1 pitch.mp3">
        </audio>
        </div>
        </td>
    </tr>
    <tr>
        <td><strong>Example 2</strong></td> 
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
  		<td>
        Q3 original:
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/10-Q3_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="text-align: right">
        Q3+Q1 p: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/10-Q3+Q1 pitch.mp3">
        </audio>
        </div>
        </td>
    </tr>
    <tr>
        <td><strong>Example 3</strong></td> 
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
  		<td>
        <div style="width: 6em">
        Q3 original: 
        </div>
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/11-Q3_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="text-align: right">
        Q3+Q1 p: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/11-Q3+Q1 pitch.mp3">
        </audio>
        </div>
        </td>
    </tr>
</table>

- Case 5: Transfer duration in Q2 to music in Q3 (Q3+Q2 d)

<table>
    <tr>
        <td><strong>Example 1</strong></td> 
        <td> </td>
        <td> </td>
        <td> </td>
    </tr>
    <tr>
  		<td>
        <div style="width: 6em">
        Q3 original: 
        </div>
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/12-Q3_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="width: 7em;text-align: right">
        Q3+Q2 d: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/12-Q3+Q2 duration.mp3">
        </audio>
        </div>
        </td>
    </tr>
    <tr>
        <td><strong>Example 2</strong></td> 
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
  		<td>
        Q3 original:
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/13-Q3_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="text-align: right">
        Q3+Q2 d: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/13-Q3+Q2 duration.mp3">
        </audio>
        </div>
        </td>
    </tr>
    <tr>
        <td><strong>Example 3</strong></td> 
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
  		<td>
        <div style="width: 6em">
        Q3 original: 
        </div>
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/14-Q3_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="text-align: right">
        Q3+Q2 d: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/14-Q3+Q2 duration.mp3">
        </audio>
        </div>
        </td>
    </tr>
</table>

- Case 6: Transfer chord in Q2 to music in Q4 (Q4+Q2 c)

<table>
    <tr>
        <td><strong>Example 1</strong></td> 
        <td> </td>
        <td> </td>
        <td> </td>
    </tr>
    <tr>
  		<td>
        <div style="width: 6em">
        Q4 original: 
        </div>
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/15-Q4_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="width: 7em;text-align: right">
        Q4+Q2 c: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/15-Q4+Q2 chord.mp3">
        </audio>
        </div>
        </td>
    </tr>
    <tr>
        <td><strong>Example 2</strong></td> 
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
  		<td>
        Q4 original:
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/16-Q4_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="text-align: right">
        Q4+Q2 c: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/16-Q4+Q2 chord.mp3">
        </audio>
        </div>
        </td>
    </tr>
    <tr>
        <td><strong>Example 3</strong></td> 
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
  		<td>
        <div style="width: 6em">
        Q4 original: 
        </div>
        </td> 
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/17-Q4_original.mp3">
        </audio>
        </div>
        </td>
        <td>
        <div style="text-align: right">
        Q4+Q2 c: 
        </div>
        </td>
        <td>
        <div style="width: 19em;text-align: center">
        <audio id="audio" controls="" preload="none">
            <source id="mp3" src="https://tayjsl97.github.io/demos/aaai_music/17-Q4+Q2 chord.mp3">
        </audio>
        </div>
        </td>
    </tr>
</table>

