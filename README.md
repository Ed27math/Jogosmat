
class TrianguloDaSabedoria:
    def __init__(self):
        self.tabuleiro = self.criar_tabuleiro()
        self.jogador_atual = 'Azul'
    
    def criar_tabuleiro(self):
        # Representação do tabuleiro: círculos como posições
        return [[' ' for _ in range(3)] for _ in range(3)]  # Exemplo simplificado
    
    def exibir_tabuleiro(self):
        for linha in self.tabuleiro:
            print(' | '.join(linha))
            print('-' * 9)
    
    def mover(self, origem, destino):
        # Lógica de movimento e verificação
        pass
    
    def verificar_vitoria(self):
        # Lógica para verificar se há um vencedor
        pass
    
    def jogar(self):
        while True:
            self.exibir_tabuleiro()
            print(f"Turno do jogador: {self.jogador_atual}")
            # Captura entrada do jogador
            # Verifica movimentos válidos
            # Atualiza o tabuleiro e verifica vitória ou empate

# Execução do jogo
jogo = TrianguloDaSabedoria()
jogo.jogar()
