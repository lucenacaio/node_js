
--
-- Estrutura da tabela 'noticias'
--

CREATE TABLE IF NOT EXISTS 'noticias' (
  'id_noticia' int(11) NOT NULL AUTO_INCREMENT,
  'titulo' varchar(60) NOT NULL,
  'noticia' varchar(200) NOT NULL,
  'data_criacao' timestamp NULL DEFAULT CURRENT_TIMESTAMP,
  'resumo' varchar(100) NOT NULL,
  'autor' varchar(30) NOT NULL,
  'data_noticia' date NOT NULL,
  PRIMARY KEY ('id_noticia')
) ENGINE=InnoDB  DEFAULT CHARSET=latin1 AUTO_INCREMENT=20 ;
