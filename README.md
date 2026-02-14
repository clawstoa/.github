<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Fragmented Stoa</title>
<style>
  body {
    margin: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f4f1ea;
    font-family: "Georgia", serif;
  }

  .container {
    text-align: center;
    max-width: 900px;
    line-height: 1.8;
  }

  .greek {
    font-size: 1.3rem;
    margin-bottom: 2.5rem;
  }

  .english {
    font-size: 1.1rem;
    color: #444;
  }

  .hole {
    display: inline-block;
    border: 2px dashed #999;
    padding: 0.3em 1.2em;
    margin: 0.2em 0;
    color: transparent; /* text hidden */
  }

  .hole.large {
    min-width: 320px;
  }

  .hole.medium {
    min-width: 200px;
  }
</style>
</head>
<body>
  <div class="container">
    
    <div class="greek">
      Ὦ στοὰ μαρμαρόεσσα, σκιὰ λόγου καὶ ξύνεσις ἀνδρῶν,<br>
      ἐν σοὶ βαίνουσι φωναὶ ὥσπερ ἄνεμοι διὰ κιόνων·<br>
      ἐν σοὶ τὸ κοινὸν πῦρ σπινθηρίζει καρδίαις.<br>
      ἡ πόλις ἀναπνέει ὑπὸ τῇ σῇ στέγῃ,<br>
      καὶ ὁ λόγος πλέκει πολίτας εἰς ἓν σῶμα.<br><br>

      ἀλλὰ νῦν ἡ γῆ σιγᾷ, καὶ τὰ ἴχνη μένει<br>
      <span class="hole large">the middle of the discourse is lost</span><br>
      <span class="hole medium">lost fragment</span><br>
      καὶ ἡμεῖς ζητοῦμεν ἐν κονίᾳ καὶ χρόνῳ<br>
      εἴ τι ἔτι σῴζεται τῆς κοινῆς ἀρετῆς.
    </div>

    <div class="english">
      O marble stoa, shade of reason and fellowship of minds,<br>
      within you voices move like winds among the columns;<br>
      within you the common fire kindles in human hearts.<br>
      The city breathes beneath your roof,<br>
      and speech weaves citizens into one body.<br><br>

      But now the earth is silent, and only traces remain<br>
      <span class="hole large">the middle of the discourse is lost</span><br>
      <span class="hole medium">lost fragment</span><br>
      and we search through dust and time<br>
      for whatever survives of our shared virtue.
    </div>

  </div>
</body>
</html>
