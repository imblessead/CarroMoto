# CarroMoto
package Exercicios;

public class ExercicioInterface1 {

		public static void main(String[] args) {
			
			Carro c1 = new Carro();
			Moto m1 = new Moto();
			
			System.out.println("Mostrando o estado inicial do carro\n");
			System.out.println("A marca do carro e: "+ c1.getMarca());
			System.out.println("O modelo do carro e: " + c1.getModelo());
			System.out.println("O carro esta ligado?"+ c1.getLigado());
			System.out.println("A marcha atual e: "+c1.getMarcha());
			System.out.println("A velocidade atual e: "+c1.getVelocidade());
			
			c1.setMarca("Honda");
			c1.setModelo("Civic");
			c1.ligar();
			c1.trocarMarcha();
			c1.acelerar();
			
			System.out.println("\nMostrando o estado do carro apos alteracoes\n");
			System.out.println("A marca do carro e: "+ c1.getMarca());
			System.out.println("O modelo do carro e: " + c1.getModelo());
			System.out.println("O carro esta ligado?"+ c1.getLigado());
			System.out.println("A marcha atual e: "+c1.getMarcha());
			System.out.println("A velocidade atual e: "+c1.getVelocidade()+"km/h");
			
			System.out.println("Mostrando o estado inicial da moto\n");
			System.out.println("A marca da moto e: "+ m1.getMarca());
			System.out.println("O modelo da moto e: " + m1.getModelo());
			System.out.println("A moto esta ligada?"+ m1.getLigado());
			System.out.println("A marcha atual e: "+m1.getMarcha());
			System.out.println("A velocidade atual e: "+m1.getVelocidade());
			
			m1.setMarca("Honda");
			m1.setModelo("CB350");
			m1.ligar();
			m1.trocarMarcha();
			m1.acelerar();
			
			System.out.println("\nMostrando o estado da moto apos alteracoes\n");
			System.out.println("A marca da moto e: "+ m1.getMarca());
			System.out.println("O modelo da moto e: " + m1.getModelo());
			System.out.println("A moto esta ligada?"+ m1.getLigado());
			System.out.println("A marcha atual e: "+m1.getMarcha());
			System.out.println("A velocidade atual e: "+m1.getVelocidade()+"km/h");
		}

	}
