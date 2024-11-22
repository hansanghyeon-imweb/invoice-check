## install

```shell
npm install invoice-check
```

## use

```ts
import { invoiceCheck, ParcelCompanyCode } from 'invoice-check'

invoiceCheck(ParcelCompanyCode.LOGEN, '680405450931')
invoiceCheck('로젠택배', '680405450931')
```

## Support

| Company        | Service                   | 작업상태 |
| -------------- | ------------------------- | ------ |
| HYUNDAI        | 롯데택배                  | 🟩 |
| KGB            | 로젠택배                  | 🟩 |
| EPOST          | 우체국                    | 🟩 |
| HANJIN         | 한진택배                  | 🟩 |
| CJGLS          | CJ대한통운                | 🟩 |
| KOREX          | 대한통운[합병]            | 🟩 |
| KDEXP          | 경동택배                  | 🟩 |
| DIRECT         | 업체직송                  | 🟩 |
| ILYANG         | 일양택배                  | 🟩 |
| CHUNIL         | 천일특송                  | 🟩 |
| AJOU           | 아주택배                  | 🟩 |
| CSLOGIS        | SC로지스                  | 🟩 |
| DAESIN         | 대신택배                  | 🟩 |
| CVS            | CVS택배                   | 🟩 |
| HDEXP          | 합동택배                  | 🟩 |
| DHL            | DHL                       | 🟩 |
| UPS            | UPS                       | 🟩 |
| FEDEX          | FEDEX                     | 🟩 |
| REGISTPOST     | 우편등기                  | 🟩 |
| EMS            | 우체국 EMS                | 🟩 |
| TNT            | TNT                       | 🟩 |
| USPS           | USPS                      | 🟩 |
| IPARCEL        | i-parcel                  | 🟩 |
| GSMNTON        | GSM NtoN                  | 🟩 |
| SWGEXP         | 성원글로벌                | 🟩 |
| PANTOS         | 범한판토스                | 🟩 |
| ACIEXPRESS     | ACI Express               | 🟩 |
| DAEWOON        | 대운글로벌                | 🟩 |
| AIRBOY         | 에어보이익스프레스        | 🟩 |
| KGLNET         | KGL네트웍스               | 🟩 |
| KUNYOUNG       | 건영택배                  | 🟩 |
| SLX            | SLX택배                   | 🟩 |
| HONAM          | 호남택배                  | 🟩 |
| LINEEXPRESS    | LineExpress               | 🟩 |
| TWOFASTEXP     | 2FastsExpress             | 🟩 |
| HPL            | 한의사랑택배              | 🟩 |
| KOREXG         | CJ대한통운특              | 🟩 |
| HANDEX         | 한덱스                    | 🟩 |
| BGF            | BGF                       | 🟩 |
| ECMS           | ECMS익스프레스            | 🟩 |
| WONDERS        | 원더스퀵                  | 🟩 |
| YONGMA         | 용마로지스                | 🟩 |
| SEBANG         | 세방택배                  | 🟩 |
| NHLOGIS        | 농협택배                  | 🟩 |
| LOTTEGLOBAL    | 롯데글로벌                | 🟩 |
| GSIEXPRESS     | GSI익스프레스             | 🟩 |
| EFS            | EFS                       | 🟩 |
| DHLGLOBALMAIL  | DHL GlobalMail            | 🟩 |
| HILOGIS        | Hi택배                    | 🟩 |
| GPSLOGIX       | GPS로직                   | 🟩 |
| CRLX           | 시알로지텍                | 🟩 |
| BRIDGE         | 브리지로지스              | 🟩 |
| HOMEINNOV      | 홈이노베이션로지스        | 🟩 |
| CWAY           | 씨웨이                    | 🟩 |
| GNETWORK       | 자이언트                  | 🟩 |
| ACEEXP         | ACE Express               | 🟩 |
| WEVILL         | 우리동네택배              | 🟩 |
| FOREVERPS      | 퍼레버택배                | 🟩 |
| WARPEX         | 워펙스                    | 🟩 |
| QXPRESS        | 큐익스프레스              | 🟩 |
| SMARTLOGIS     | 스마트로지스              | 🟩 |
| HOMEPICK       | 홈픽택배                  | 🟩 |
| GTSLOGIS       | GTS로지스                 | 🟩 |
| ESTHER         | 에스더쉬핑                | 🟩 |
| INTRAS         | 로토스                    | 🟩 |
| EUNHA          | 은하쉬핑                  | 🟩 |
| UFREIGHT       | 유프레이트 코리아         | 🟩 |
| LSERVICE       | 엘서비스                  | 🟩 |
| TPMLOGIS       | 로지스밸리                | 🟩 |
| ZENIELSYSTEM   | 제니엘시스템              | 🟩 |
| ANYTRACK       | 애니트랙                  | 🟩 |
| JLOGIST        | 제이로지스트              | 🟩 |
| CHAINLOGIS     | 두발히어로(4시간당일택배) | 🟩 |
| QRUN           | 큐런                      | 🟩 |
| FRESHSOLUTIONS | 프레시솔루션              | 🟩 |
| HIVECITY       | 하이브시티                | 🟩 |
| HANSSEM        | 한샘                      | 🟩 |
| SFC            | SFC(Santai)               | 🟩 |
| JNET           | J-NET                     | 🟩 |
| GOODSTOLUCK    | 굿투럭                    | 🟩 |
| GENIEGO        | 지니고                    | 🟩 |
| PANASIA        | 판아시아                  | 🟩 |
| ELIAN          | elianpost                 | 🟩 |
| LOTTECHILSUNG  | 롯데칠성                  | 🟩 |
| SBGLS          | SBGLS                     | 🟩 |
| ALLTAKOREA     | 올타코리아                | 🟩 |
| YUNDA          | yunda express             | 🟩 |
| VALEX          | 발렉스                    | 🟩 |
| KOKUSAI        | 국제익스프레스            | 🟩 |
| XINPATEK       | 윈핸드해운항공            | 🟩 |
| HEREWEGO       | 탱고앤고                  | 🟩 |
| WOONGJI        | 웅지익스프레스            | 🟩 |
| PINGPONG       | 핑퐁                      | 🟩 |
| YDH            | YDH                       | 🟩 |
| CARGOPLEASE    | 화물부탁해                | 🟩 |
| LOGISPOT       | 로지스팟                  | 🟩 |
| FRESHMATES     | 프레시메이트              | 🟩 |
| VROONG         | 부릉                      | 🟩 |
| NKLS           | NK로지솔루션              | 🟩 |
| DODOFLEX       | 도도플렉스                | 🟩 |
| ETOMARS        | 이투마스                  | 🟩 |
| SHIPNERGY      | 배송하기좋은날            | 🟩 |
| VENDORPIA      | 에이스물류                | 🟩 |
| COSHIP         | 캐나다쉬핑                | 🟩 |
| GDAKOREA       | 지디에이코리아            | 🟩 |
