[![License](https://img.shields.io/badge/license-AGPL-blue.svg?style=flat)](https://opensource.org/licenses/AGPL-3.0)
[![Documentation](https://img.shields.io/badge/docs-latest-brightgreen.svg?style=flat)](http://docs.chan.org)
[![Support on StackOverflow](https://img.shields.io/badge/support-StackOverflow-yellowgreen.svg?style=flat)](https://stackoverflow.com/questions/tagged/ckan)
[![Build Status](https://circleci.com/gh/ckan/ckan.svg?style=shield)](https://circleci.com/gh/ckan/ckan)
[![Coverage Status](https://coveralls.io/repos/github/ckan/ckan/badge.svg?branch=master)](https://coveralls.io/github/ckan/ckan?branch=master)
[![Chat on Gitter](https://badges.gitter.im/gitterHQ/gitter.svg)](https://app.gitter.im/#/room/#Bg_Rehberi:gitter.im)




### Amaç
* Kamu kurumlarında kullanılabilecek açık kaynaklı projelerin yaygınlaştırılması amacı ile özellikle uzman ve kullanıcılar tarafından  kategorilerine göre açık kaynak uygulamaların listesinin oluşturulması 

# İçindekiler

## 1. Sunucu Sistemleri
- İşletim Sistemi
- Veri Tabanı Yönetim Sistemi
- Dizin Yönetimi ve Kullanıcı Cihaz Yönetimi Sistemleri
- E-Posta Sistemi
- Alan Adı Sunucu Sistemi (DNS)
- Dinamik Makine Yapılandırma Protokolü (DHCP)
- Ağ İlkesi Sunucusu (NPS, RADIUS)
- Web ve Uygulama Sunucusu
- Dosya Sunucusu
- Video Konferans Sistemi
- Diğer

## 2. Sanallaştırma Ortamları
- Sunucu Sanallaştırma
- Konteyner Teknolojileri
- Depolama Alanı Sanallaştırma
- Ağ Sanallaştırma
- Masaüstü Sanallaştırma ve Uygulama Sanallaştırma
- Diğer

## 3. Siber Güvenlik Yazılımları
- Güvenlik Duvarı
- Web Uygulama Güvenlik Duvarı (WAF)
- Saldırı Tespit / Önleme Sistemi (IDS / IPS)
- Güvenlik Bilgileri ve Olay Yönetimi (SIEM)
- Ağ Erişimi Kontrol Sistemi (NAC)
- E-Posta Güvenliği
- Sanal Özel Ağ Sistemi (VPN)
- Ağ ve Sunucu Sistemleri İzleme Sistemi
- Anti-virüs
- Güvenlik Zafiyet Yönetimi
- Diğer

## 4. Son Kullanıcı Uygulamaları
- İşletim Sistemi
- Kurumsal Uygulamalar
- Ofis Uygulamaları
- Multimedya Uygulamaları
- Mesleki Uygulamalar
- Web Uygulama Yazılımları
- Diğer

## 5. Diğer












### Proje  Aşamaları:
- Öncelik
1. Kategorilerin ve Listenin oluşturulması
1. Uyuglaması Mümkün olanlar için  uygulama örnekleri geliştirmek.
4. Listeyi sürekli güncel tutumak ve yenilemek

# Kamu Kurumları için Açık Kaynak Projeler

## Sunucu Sistemleri

| Proje            | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| Linux            | Güvenli, esnek ve özelleştirilebilir işletim sistemi | Sunucu işletim sistemi olarak geniş bir kullanım yelpazesi | ⭐⭐⭐⭐⭐ | [GitHub](https://github.com/torvalds/linux) |
| PostgreSQL       | Güçlü, açık kaynaklı ilişkisel veritabanı yönetim sistemi | Kurumsal uygulamalar, web tabanlı uygulamalar, veri depolama ve analizi | ⭐⭐⭐⭐ | [Web Sitesi](https://www.postgresql.org/) |
| Zimbra           | E-posta, takvim ve işbirliği için açık kaynak platform | Kurumsal e-posta çözümleri, ekip çalışması ve iletişim | ⭐⭐⭐ | [Web Sitesi](https://www.zimbra.com/) |
| BIND             | İnternetin en yaygın DNS sunucusu yazılımı    | Alan adı çözümlemesi, DNS hizmetleri               | ⭐⭐⭐⭐ | [Web Sitesi](https://www.isc.org/bind/) |
| ISC DHCP         | Dinamik IP adresi atama ve yapılandırma için DHCP sunucusu | Ağ yapılandırması, IP adres yönetimi               | ⭐⭐⭐ | [Web Sitesi](https://www.isc.org/dhcp/) |
| FreeRADIUS      | RADIUS protokolüne dayalı ağ erişim denetim (NAC) sunucusu | Ağ erişim denetimi, kablosuz ağ güvenliği          | ⭐⭐⭐⭐ | [GitHub](https://github.com/FreeRADIUS/freeradius-server) |
| Apache HTTP Server | Dünyanın en popüler web sunucusu             | Web siteleri, web uygulamaları, sunucu yanı yazılımlar | ⭐⭐⭐⭐ | [Web Sitesi](https://httpd.apache.org/) |
| Samba            | SMB/CIFS protokolleri üzerinden dosya ve yazıcı paylaşımı sağlayan yazılım | Dosya ve yazıcı paylaşımı, ağ dosya depolama çözümleri | ⭐⭐⭐ | [Web Sitesi](https://www.samba.org/) |
| Jitsi            | Güvenli ve ölçeklenebilir video konferans çözümü | Uzaktan iletişim, eğitim, işbirliği                | ⭐⭐⭐⭐ | [GitHub](https://github.com/jitsi) |
| Nextcloud        | Dosya depolama, paylaşım ve işbirliği platformu | Bulut depolama, işbirliği, dosya senkronizasyonu   | ⭐⭐⭐⭐ | [GitHub](https://github.com/nextcloud) |



## Yönetim ve İş Süreçleri

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| OpenProject      | Proje yönetim yazılımı                        | Proje ve görev yönetimi, zaman çizelgeleri         | ⭐⭐⭐⭐ | [Web Sitesi](https://www.openproject.org/) |
| ERPNext          | Kurumsal kaynak planlama yazılımı             | Muhasebe, envanter, İK, satış, satın alma          | ⭐⭐⭐ | [GitHub](https://github.com/frappe/erpnext) |

## Veri Analizi ve Görselleştirme

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| Metabase         | Kolayca kurulabilen veri analizi platformu    | Raporlama, veri analizi, veri görselleştirme       | ⭐⭐⭐⭐ | [GitHub](https://github.com/metabase/metabase) |
| Grafana          | Açık kaynaklı metrik analizi ve izleme platformu | Veritabanı sorgulamaları, gösterge panelleri, izleme | ⭐⭐⭐⭐ | [GitHub](https://github.com/grafana/grafana) |

## Güvenlik

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| OpenVAS          | Açık kaynaklı güvenlik açığı tarama sistemi   | Ağ güvenliği taramaları, güvenlik açıklarını belirleme | ⭐⭐⭐⭐ | [GitHub](https://github.com/greenbone/openvas) |
| OSSEC            | Host bazlı saldırı tespit sistemi (HIDS)      | Güvenlik izleme, olay müdahale                      | ⭐⭐⭐⭐ | [GitHub](https://github.com/ossec/ossec-hids) |

## Vatandaş Hizmetleri

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| FixMyStreet     | Vatandaşların altyapı sorunlarını bildirmesini sağlayan platform | Yol, kaldırım, park sorunları | ⭐⭐⭐⭐⭐ | [Web Sitesi](https://www.fixmystreet.com/) |

## Sanallaştırma Ortamları

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
|       |                         |          |  |  |
|          |              |           | |  |









