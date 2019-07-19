# Spring core annotation
------------------------
## DI-Related Annotations

* @Autowired
	* sử dung @Autowired to đánh dấu cho spring biết rằng: ta đã tiêm phần tử này vào để sử dụng không cần phải phụ thuộc vào phần tử kia.Phụ thuộc ở đây là khi class Y được khởi tạo new Object() trong 1 class X thì Y phụ thuộc vào X.
	* class X {
		private Y y = new Y();
	}
	* DI : class X {
		@Autowired
		private Y y;
	}
	* Có 3 loại Injection:
		* Constructor Injection : 
			@Autowired
		    Car(Engine engine) {
		        this.engine = engine;
		    }
		* Setter Injection:
			@Autowired
			void setEngine(Engine engine) this.engine = engine;
		* Field Injection:
			@Autowired
	    	Engine engine;
	* Sự khác nhau giữa Setter injection và Constructor Injection :