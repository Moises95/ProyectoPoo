ProyectoPoo
===========
package biblioteca;

public class LibrosRevistas {
	
	public String autor;
	public String editor;
	public String edicion;
	public String editorial;
	public String genero;
	public int calificacion;
	public String titulo;
	public boolean disponible;
	
	public String getTitulo() {
		return titulo;
	}
	public void setTitulo(String pTitulo) {
		this.titulo = pTitulo;
	}
	public boolean isDisponible() {
		return disponible;
	}
	public void setDisponible(boolean pDisponible) {
		this.disponible = pDisponible;
	}
	public String getAutor() {
		return autor;
	}
	public void setAutor(String pAutor) {
		this.autor = pAutor;
	}
	public String getEditor() {
		return editor;
	}
	public void setEditor(String pEditor) {
		this.editor = pEditor;
	}
	public String getEdicion() {
		return edicion;
	}
	public void setEdicion(String pEdicion) {
		this.edicion = pEdicion;
	}
	public String getEditorial() {
		return editorial;
	}
	public void setEditorial(String pEditorial) {
		this.editorial = pEditorial;
	}
	public String getGenero() {
		return genero;
	}
	public void setGenero(String pGenero) {
		this.genero = pGenero;
	}
	public int getCalificacion() {
		return calificacion;
	}
	public void setCalificacion(int pCalificacion) {
		this.calificacion = pCalificacion;
	}
	

}
