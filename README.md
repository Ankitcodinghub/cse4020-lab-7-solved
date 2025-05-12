# cse4020-lab-7-solved
**TO GET THIS SOLUTION VISIT:** [CSE4020 Lab 7 Solved](https://www.ankitcodinghub.com/product/cse4020-lab-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91693&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE4020 Lab 7 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
&nbsp;

<ol>
<li>Write a program that draws a color-changing cube.
<ol>
<li>Set the window title to <strong>your student ID</strong> and the window size to (480,480).</li>
<li>Start from the code in 7-Lighting&amp;Shading slides. Draw a flat-shaded cube. Make sure camera manipulation shortcuts ‘1’,’3′,2’w, work</li>
<li></li>
<li>Use the following light setting:</li>
</ol>
</li>
</ol>
lightPos <strong>=</strong> <strong>(</strong>3.<strong>,</strong>4.<strong>,</strong>5.<strong>,</strong>1.<strong>)</strong>

glLightfv<strong>(</strong>GL_LIGHT0<strong>,</strong> GL_POSITION<strong>,</strong> lightPos<strong>)</strong>

&nbsp;

ambientLightColor <strong>=</strong> <strong>(</strong>.1<strong>,</strong>.1<strong>,</strong>.1<strong>,</strong>1.<strong>)</strong>

glLightfv<strong>(</strong>GL_LIGHT0<strong>,</strong> GL_AMBIENT<strong>,</strong> ambientLightColor<strong>)</strong>

&nbsp;

specularObjectColor <strong>=</strong> <strong>(</strong>1.<strong>,</strong>1.<strong>,</strong>1.<strong>,</strong>1.<strong>)</strong>

glMaterialfv<strong>(</strong>GL_FRONT<strong>,</strong> GL_SPECULAR<strong>,</strong> specularObjectColor<strong>)</strong>

glMaterialfv<strong>(</strong>GL_FRONT<strong>,</strong> GL_SHININESS<strong>,</strong> 10<strong>)</strong>

&nbsp;

<ol>
<li>If you press or repeat a key, the diffuse &amp; specular color of the light and the ambient &amp; diffuse color of the object should be changed as shown in the Table:</li>
</ol>
<table width="371">
<tbody>
<tr>
<td width="36"><strong>Key </strong></td>
<td width="335"><strong>Action </strong></td>
</tr>
<tr>
<td width="36">A</td>
<td width="335">Change the light color to red</td>
</tr>
<tr>
<td width="36">S</td>
<td width="335">Change the light color to green</td>
</tr>
<tr>
<td width="36">D</td>
<td width="335">Change the light color to blue</td>
</tr>
<tr>
<td width="36">F</td>
<td width="335">Change the light color to white</td>
</tr>
<tr>
<td width="36">Z</td>
<td width="335">Change the object color to red</td>
</tr>
<tr>
<td width="36">X</td>
<td width="335">Change the object color to green</td>
</tr>
<tr>
<td width="36">C</td>
<td width="335">Change the object color to blue</td>
</tr>
<tr>
<td width="36">V</td>
<td width="335">Change the object color to white</td>
</tr>
</tbody>
</table>
<ol>
<li>Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)</li>
</ol>
&nbsp;

<ol start="2">
<li>Write a program that draws a smooth-shaded cube.
<ol>
<li>Set the window title to <strong>your student ID</strong> and the window size to (480,480).</li>
<li>Start from the code in 7-Lighting&amp;Shading slides. Make sure camera manipulation’1′,’3′,2’w, work</li>
</ol>
</li>
</ol>
<h1></h1>
<ol>
<li>Use <strong>glDrawElements(),</strong> not glDrawArray(). Refer the code in 6-Viewing&amp;projection2, Mesh slides.</li>
<li>Hint: In Gouraud shading, one vertex has only one normal. This makes using glDrawElements() easier.</li>
<li>Use the following normal vector data:</li>
<li>If you press or repeat a key, the ambient &amp; diffuse color of the object should be changed as shown in the Table:</li>
</ol>
<table width="371">
<tbody>
<tr>
<td width="36"><strong>Key </strong></td>
<td width="335"><strong>Action </strong></td>
</tr>
<tr>
<td width="36">R</td>
<td width="335">On/Off the object color of red</td>
</tr>
<tr>
<td width="36">G</td>
<td width="335">On/Off the object color of green</td>
</tr>
<tr>
<td width="36">B</td>
<td width="335">On/Off the object color of blue</td>
</tr>
</tbody>
</table>
<ol start="2">
<li>Expected result: Uploaded LabAssignment7-2.mp4</li>
<li>Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)</li>
</ol>
&nbsp;
