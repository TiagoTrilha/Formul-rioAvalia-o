<!DOCTYPE html>
<html>
<head>
  <title>Formulário de Avaliação</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>
<body>
  <div class="container">
    <div class="header">
      <div class="header-box">
        <h1>Formulário de Avaliação</h1>
      </div>
    </div>

    <form id="form-avaliacao">
      <div class="question-box">
        <div class="question">
          <div class="question-inner">
            <p>Nome:</p>
            <input type="text" name="nome" required>
          </div>
        </div>
        <div class="question">
          <div class="question-inner">
            <p>1. Utilizam ficha de controle de secagem?</p>
            <div class="options">
              <label><input type="radio" name="pergunta1" value="2"> Sim</label>
              <label><input type="radio" name="pergunta1" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>2. Faz todas as anotações que estão na ficha?</p>
            <div class="options">
              <label><input type="radio" name="pergunta2" value="2"> Sim</label>
              <label><input type="radio" name="pergunta2" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>3. Avalia com seu colega o rendimento da secagem diariamente conforme planilha?</p>
            <div class="options">
              <label><input type="radio" name="pergunta3" value="3"> Sim</label>
              <label><input type="radio" name="pergunta3" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>4. Efetua a limpeza com ar ou água em todo secador regularmente?</p>
            <div class="options">
              <label><input type="radio" name="pergunta4" value="3"> Sim</label>
              <label><input type="radio" name="pergunta4" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>5. Efetua regulagens necessárias na mesa do secador?</p>
            <div class="options">
              <label><input type="radio" name="pergunta5" value="2"> Sim</label>
              <label><input type="radio" name="pergunta5" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>6. Efetua medições de umidade dos grãos a cada 15 minutos?</p>
            <div class="options">
              <label><input type="radio" name="pergunta6" value="3"> Sim</label>
              <label><input type="radio" name="pergunta6" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>7. Efetua mudança de velocidade na mesa do secador conforme entrada do grão (umidade)?</p>
            <div class="options">
              <label><input type="radio" name="pergunta7" value="3"> Sim</label>
              <label><input type="radio" name="pergunta7" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>8. Possui padrão de saída de umidade do grão?</p>
            <div class="options">
              <label><input type="radio" name="pergunta8" value="3"> Sim</label>
              <label><input type="radio" name="pergunta8" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>9. Possui lenha padronizada (lascada)?</p>
            <div class="options">
              <label><input type="radio" name="pergunta9" value="3"> Sim</label>
              <label><input type="radio" name="pergunta9" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>10. Possui local fechado para armazenamento da lenha?</p>
            <div class="options">
              <label><input type="radio" name="pergunta10" value="2"> Sim</label>
              <label><input type="radio" name="pergunta10" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>11. É monitorado a temperatura da fornalha regularmente?</p>
            <div class="options">
              <label><input type="radio" name="pergunta11" value="2"> Sim</label>
              <label><input type="radio" name="pergunta11" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>12. Sabe regular o secador conforme depressões?</p>
            <div class="options">
              <label><input type="radio" name="pergunta12" value="3"> Sim</label>
              <label><input type="radio" name="pergunta12" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>13. Sabe regular o secador para utilizar o resfriamento (caso tenha)?</p>
            <div class="options">
              <label><input type="radio" name="pergunta13" value="2"> Sim</label>
              <label><input type="radio" name="pergunta13" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>14. Sabe quando utilizar a secagem de coluna inteira?</p>
            <div class="options">
              <label><input type="radio" name="pergunta14" value="2"> Sim</label>
              <label><input type="radio" name="pergunta14" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>15. Sabe a capacidade de secagem do secador em tonelada/hora?</p>
            <div class="options">
              <label><input type="radio" name="pergunta15" value="2"> Sim</label>
              <label><input type="radio" name="pergunta15" value="0"> Não</label>
            </div>
          </div>
        </div>

        <div class="question">
          <div class="question-inner">
            <p>16. Consegue baixar o teor de umidade do grão de soja de 18% para 13% em 1 hora?</p>
            <div class="options">
              <label><input type="radio" name="pergunta16" value="3"> Sim</label>
              <label><input type="radio" name="pergunta16" value="0"> Não</label>
            </div>
          </div>
        </div>

      </div>

    
      <button type="submit">Enviar</button>
    </form>

    <div id="result" class="result"></div>

  </div>

  <script src="script.js"></script>
</body>
</html>
