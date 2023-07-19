it('should set title and subtitle correctly based on route query params', () => {
      expect(component.title).toEqual('Search Results');
      expect(component.subtitle).toEqual('Claims');
  });
