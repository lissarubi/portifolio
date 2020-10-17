<template>
  <main>
    <h1>Ederson Ferreira</h1>
    <h2>Backend Developer</h2>

    <h1>My Stack</h1>

    <div class="buttonBox">
      <Button color="25E628" name="NodeJS" link="https://nodejs.org/en/" />
      <Button color="5E3BE6" name="PHP" link="https://www.php.net/" />
      <Button color="E66953" name="Ruby" link="https://www.ruby-lang.org/" />
      <Button color="E6D125" name="JS" link="https://www.javascript.com/" />
      <Button color="4B25E6" name="Laravel" link="laravel.com/" />
      <Button color="209922" name="Vue" link="https://vuejs.org/" />
      <Button color="7C5CFF" name="MySQL" link="https://www.mysql.com/" />
      <Button
        color="306DE6"
        name="PostgreSQL"
        link="https://www.postgresql.org/"
      />
      <Button color="9783EA" name="Linux" link="https://www.linux.org/" />
    </div>

    <h1>Social Networks</h1>
    <div class="buttonBox">
      <Button
        color="3667E3"
        name="Twitter"
        link="https://twitter.com/edersondev_/"
      />
      <Button
        color="6336E3"
        name="Twitch"
        link="https://twitch.tv/edersondeveloper/"
      />
      <Button
        color="7E6694"
        name="GitHub"
        link="https://github.com/edersonferreira/"
      />
    </div>

    <h1>Best Projects</h1>
    <Project name="MarkPDF" about="CLI Program to generate PDF's based in Markdown files" link="markpdf" />
    <Project name="Urano" about="CLI Program to create Twitch Chatbots" link="urano-twitch" />
    <Project name="Ruby4noobs" about="A Ruby tutorial to noobs in Portuguese" link="ruby4noobs" />
    <Project name="PostgreSQL4noobs" about="A PostgreSQL tutorial to noobs in Portuguese" link="postgresql4noobs" />
    <Project name="Relax Lurk" about="CLI Program to lurk Twitch channels" link="relax-lurk" />
  </main>
</template>

<script>
import Button from './Button.vue';
import Project from './Project.vue';

export default {
  name: 'Portifolio',
  components: {
    Button,
    Project,
  },
};
</script>

<style>
@import '../assets/css/portifolio.css';
</style>
