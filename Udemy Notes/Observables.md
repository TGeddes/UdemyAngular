Observables
An observable is a data source.
Observer: handle normal data, handle error, handle completion. This is the code that you write.
You use observable to handle asynchronous tasks.
Observables are constructs in which you subscribe where you are informed in changes in data.
Some observables don’t stop emitting values just because you aren’t using them.
Observables provided by angular automatically unsubscribe.
If you have a custom observable remember to always unsubscribe.
Once an observable sends an error it kills the observable.
Once an observable is complete it is done and will not emit any more data.
Error cancels observable it does not complete it.
Subjects you can subscribe to but you can call next outside of the observable.
Use subject not event emitter. Subject is more efficient behind the scenes.
You have to unsubscribe from a subject.
Don’t use subject over emitter in Output.

