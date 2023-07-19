it('should set title and subtitle correctly based on route query params', () => {
      expect(component.title).toEqual('Search Results');
      expect(component.subtitle).toEqual('Claims');
  });


describe('ComponentName', () => {
  let component: ComponentName;
  let fixture: ComponentFixture<ComponentName>;

  beforeEach(async(() => {
    TestBed.configureTestingModule({
      declarations: [ ComponentName ]
    })
    .compileComponents();
  }));

  beforeEach(() => {
    fixture = TestBed.createComponent(ComponentName);
    component = fixture.componentInstance;
    fixture.detectChanges();
  });
  
