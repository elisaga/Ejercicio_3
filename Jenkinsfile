pipeline{
    agent any
    stages{
        stage("Creación de fichero"){
            steps{
                script{
                    def contenido = "Mi interprete favorito es Keira Knightley"
                    writeFile(file: "Ejercicio_3.txt", text: contenido)
                }
            }

        }
        stage("Lectura de fichero"){
            steps{
                script{
                    def lectura = readFile("Ejercicio_3.txt")
                    println lectura
                }
            }
        }
    }
}
