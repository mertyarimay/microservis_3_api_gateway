# Spring Cloud Gateway
[GitHub]()



## Api Gateway
-Tüm mikroservislere  gelen istekleri yöneten  bir geçit.
-Api Gateway:Tüm istemci istekleri yönetecek  ve ilgili mikroservislere yönlendirecek.

## spring-cloud-starter-gateway
- Spring cloud gateway in temel bağımlılığıdır ve bu bağımlılık  ,tamamen reactor netty üzerine inşa edilmiştir reaktif  programlama modelini kullanır.
- **Reactive Programming:** Bu starter ,spring webflux üzerine inşa edilmiştir buda uygulamanın reaktif ,asenkron ve yüksek performanslı olmasını sağlıyor
- **Netty:** Netty,düşük seviyeli bir ağ uygulaması çatısıdır
- **KULLANIM SENARYOSU:**
- Yüksek performanslı,ölçeklenebilir ve asenkreon işlemlerin  ön planda olduğu  gateway çözümleri için tercih edilir.
- Genellikle mikro servis mimarilerinde tercih edilir.

## spring-cloud-starter-gateway-mvc
-Spring cloud gatewayın spring mvc tabanlı  bir sürümüdür.
-Senkron işlem gerektirmektedir.