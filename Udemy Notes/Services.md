Services
Services app: Service app connects to other components to outsource how something is done. They are just normal typescript files. To call a service initialized it into the constructor using private and add providers in the component with a link to the service.
Dependency injector: Injects an instance of a class into a component. Is a hierarchical injector. 
If you inject into AppModule the same instance of the service is available application-wide.
If you inject into the AppComponent the same instance is available for all components but nor for other services.
If you inject into a single component with not child components will only be available for the single component.
If you inject a service into a service remember to add the @Injectable() tag at the top of the file.

