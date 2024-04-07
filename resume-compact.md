---

layout: default  
  
---
<section class="resume-container page-container">
    <div class="compact-resume-heading">
        <h2 class="resume-header no-print">Resume Compact</h2>
        <a class="no-print" href="/chris-del-portfolio">
            <div class="cir icon">CD</div>
        </a>
        <div class="no-print">An Compact, Printer-Frienly Explanation of my Experience</div>
        <input class="no-print" type="button" value="Print Resume" onClick="window.print()">
    </div>
    <div class="resume-content">
        <div class="resume-title">
            <h2>Chris Dielschnieder</h2>
            <h4>SOFTWARE DEVELOPER</h4>
            <div class="print-only">Phone: 306-519-0138</div>
            <div class="print-only">Email: chrisdel.tech9@gmail.com</div>
        </div>
        <div class="skills-print-container">
            <div id="resume-Languages">
                <h3>TOP LANGUAGES AND TECH</h3>
                <table>
                    <tr>
                        <th>Tech</th>
                        <th>Years</th>
                    </tr>
                    <tr>
                        <td>Javascript/ES6</td>
                        <td>5+</td>
                    </tr>
                    <tr>
                        <td>React</td>
                        <td>5</td>
                    </tr>
                    <tr>
                        <td>Typescript</td>
                        <td>2</td>
                    </tr>
                    <tr>
                        <td>Python/Flask</td>
                        <td>5+</td>
                    </tr>
                    <tr>
                        <td>C/C++</td>
                        <td>5+</td>
                    </tr>
                    <tr>
                        <td>SQL/Postgres</td>
                        <td>5</td>
                    </tr>
                    <tr>
                        <td>Elixir/Phoenix</td>
                        <td>1</td>
                    </tr>
                    <tr>
                        <td>Rails/Ruby</td>
                        <td>2</td>
                    </tr>
                </table>
            </div>
            <div id="top-skills">
                <h3>TOP SKILLS</h3>
                <ul>
                    <li>Creative Problem Solving</li>
                    <li>Full-Stack Development</li>
                    <li>Web Application Development</li>
                    <li>Object Oriented Design</li>
                    <li>Public Speaking/Writing</li>
                    <li>Ability to Work Unsupersived</li>
                    <li>Networks and Protocols</li>
                    <li>Open Source Contribution</li>
                </ul>
            </div>
        </div>
        {% include work_experience.html %}
        {% include education.html %}

    </div>
</section>
