# camtest

Be sure to run bower and npm to load all dependencies.  This app has been tested on android (multipe versions up to 6.01); so far
it runs only via 'ionic run android' but fails when downloaded and installed via adobe.build with the following error:

ionic.bundle.js:26799 ReferenceError: Camera is not defined
    at ChildScope.$scope.takePicture (app.js:32)
    at fn (eval at compile (ionic.bundle.js:27643), <anonymous>:4:224)
    at ionic.bundle.js:65429
    at ChildScope.$eval (ionic.bundle.js:30400)
    at ChildScope.$apply (ionic.bundle.js:30500)
    at HTMLButtonElement.<anonymous> (ionic.bundle.js:65428)
    at defaultHandlerWrapper (ionic.bundle.js:16792)
    at HTMLButtonElement.eventHandler (ionic.bundle.js:16780)
    at triggerMouseEvent (ionic.bundle.js:2953)
    at tapClick (ionic.bundle.js:2942)
