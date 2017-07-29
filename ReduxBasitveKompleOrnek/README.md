İnternette REDUX ile ilgili pek çok örnek var ancak Dan Abramov'un örnekleri de dahil olmak üzere pek çoğu ya çok basit ya da çok ayrıntılı. Mesela TODO örneği. Tek bir "state" üzerinden oldukça basit bir şekilde anlatılmış. Diğer örnekler ise oldukça ayrıntlı olduğu için REDUX'ı kafamda tam anlamıyla oturtmam uzun bir zaman aldı. Tek bir reducer örneği ile 2 reducer örneği arasındaki fark, 2 reducer örneği ile 100 reducer örneği arasındaki farktan kat be kat fazla. Bu sebeple birden fazla state'in olduğu basit bir örneğin başlangıç aşamasında çok daha yardımcı olacağını düşünüyorum.

Ayrıca Babel vs. uğraşmadan direk tarayıcıda çalışıp debug edilebilecek Vanilla JS kodunun başlangıç aşamasında çok daha yardımcı olabileceğini düşündüm. Bu sebeple bu örneği öncelikle "kendime notlar" şeklinde hazırladım. Ancak başkalarına da yardımcı olursa ne mutlu bana.

Örnek tek bir html sayfasından ve içerisine gömülü olan scriptten oluşuyor.

- Action (4 tane)
- Action creator (4 tane)
- Reducer (2 tane)
- Initial State
- Root Reducer
- Dispatch Action

gibi REDUX'ın temel bileşenlerini olabilecek en basit şekilde anlatmaya çalıştım. redux-thunk örneği ile birleştirilmesini ise gelecek bir zamanda yüklemeye çalışacağım.