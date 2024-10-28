
 - start kamailio
   
   docker run --net=host --name kamailio_tmp_topoh -v .:/etc/kamailio   kamailio/kamailio-ci

 - start uas
   
   ./uas.sh
   
 - start uac
   
   ./uac.sh

## WITH topoh

 ![with_topoh](./with_topoh.png)
 ![with_topoh_log](./with_topoh_log.png)

## WITHOUT topoh

 ![without_topoh](./without_topoh.png)
