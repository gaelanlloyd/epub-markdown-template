# Chapter One

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed purus dolor, sagittis placerat placerat eu, posuere in mauris. Aliquam sodales viverra quam ac dictum. Vestibulum est orci, laoreet id hendrerit sed, molestie id justo. Duis lectus erat, porttitor ut pharetra ac, viverra ac odio. Nam purus tellus, rutrum at ullamcorper a, lobortis sit amet nulla. Curabitur in quam id augue facilisis suscipit eu a ante. Praesent sit amet neque eget nisi tempus euismod sed ut arcu. Duis et dui eget turpis gravida placerat. Aliquam erat volutpat. Ut non diam nulla. Integer felis sapien, faucibus in egestas ut, bibendum non nibh.

Donec vel dapibus erat. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum quam augue, semper sit amet vehicula sit amet, pellentesque pellentesque nisi. Proin vel tellus quam. Ut vehicula massa a sem mollis placerat. In venenatis ligula in arcu egestas ut congue felis rhoncus. Nunc sollicitudin eleifend lacus vel vestibulum. Sed velit urna, condimentum et lobortis id, semper nec metus. Ut mattis tortor id tortor dignissim sodales. Phasellus et varius tellus. Morbi id fermentum lectus. Sed sed malesuada ipsum. Aenean elit nisi, commodo nec gravida posuere, venenatis ac odio. Phasellus malesuada dictum faucibus. Duis vitae urna at massa placerat varius nec a quam. Morbi nec tortor purus, at bibendum nulla.

- Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- Sed purus dolor, sagittis placerat placerat eu, posuere in mauris.
- Aliquam sodales viverra quam ac dictum.
- Vestibulum est orci, laoreet id hendrerit sed, molestie id justo.
- Duis lectus erat, porttitor ut pharetra ac, viverra ac odio.
- Nam purus tellus, rutrum at ullamcorper a, lobortis sit amet nulla.
- Curabitur in quam id augue facilisis suscipit eu a ante.
- Praesent sit amet neque eget nisi tempus euismod sed ut arcu.
- Duis et dui eget turpis gravida placerat.
- Aliquam erat volutpat.
- Ut non diam nulla.
- Integer felis sapien, faucibus in egestas ut, bibendum non nibh.

Vivamus sed volutpat nunc. Aenean aliquam pretium lectus, in adipiscing orci tempus id. Vestibulum dapibus metus sit amet sapien eleifend at ullamcorper risus iaculis. Pellentesque eu diam porta justo malesuada aliquam ac in magna. Integer sed metus eget tortor tempor laoreet. Aenean ac metus augue, varius sodales lacus. Aliquam erat volutpat.

1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
1. Sed purus dolor, sagittis placerat placerat eu, posuere in mauris.
1. Aliquam sodales viverra quam ac dictum.
1. Vestibulum est orci, laoreet id hendrerit sed, molestie id justo.
1. Duis lectus erat, porttitor ut pharetra ac, viverra ac odio.
1. Nam purus tellus, rutrum at ullamcorper a, lobortis sit amet nulla.
1. Curabitur in quam id augue facilisis suscipit eu a ante.
1. Praesent sit amet neque eget nisi tempus euismod sed ut arcu.
1. Duis et dui eget turpis gravida placerat.
1. Aliquam erat volutpat.
1. Ut non diam nulla.
1. Integer felis sapien, faucibus in egestas ut, bibendum non nibh.

Sed vehicula urna nec purus feugiat lacinia. Proin est sapien, laoreet sit amet tristique in, dictum vel tellus. Donec sed libero sit amet enim dictum gravida. Ut facilisis consequat nisl ac pulvinar. Aliquam iaculis bibendum mauris vitae rhoncus. Quisque malesuada ullamcorper velit, quis fringilla dui ornare at. Nam tincidunt suscipit tortor malesuada hendrerit. Aenean at imperdiet erat. In volutpat eros ut massa ultrices nec condimentum diam pulvinar. Sed facilisis dapibus nunc, a scelerisque tortor condimentum vel. Curabitur varius erat cursus ligula mollis ultricies interdum augue egestas. Mauris sed tempus mi. Nullam consectetur ligula et augue semper posuere. Vivamus pulvinar imperdiet nisi, eu facilisis eros consectetur eu.

```bash
timestamp=$(date +'%Y-%m-%d-%H%M%S')
outputFile="/home/gaelan/wsh5-meta/result-$timestamp.txt"

page[12640]="Winshuttle reseller partners"
page[12649]="Customer presentations"
.
.
.
page[9998]="SAP and Excel"

echo "Saving output to $outputFile"

# start the output file with single >
echo "id-orig,id-new,title" > $outputFile

n=1
max=${#page[@]}

for i in "${!page[@]}"
do

    thisID=$i
    thisTitle=${page[$i]}


    # ACTUAL RUN
    thisNewID=`eval $thisCommand`
    echo "- $i ($n/$max)"
    echo "$i,$thisNewID,$thisTitle" >> $outputFile  # append
    n=$((n+1))

done
```

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed purus dolor, sagittis placerat placerat eu, posuere in mauris. Aliquam sodales viverra quam ac dictum. Vestibulum est orci, laoreet id hendrerit sed, molestie id justo. Duis lectus erat, porttitor ut pharetra ac, viverra ac odio. Nam purus tellus, rutrum at ullamcorper a, lobortis sit amet nulla. Curabitur in quam id augue facilisis suscipit eu a ante. Praesent sit amet neque eget nisi tempus euismod sed ut arcu. Duis et dui eget turpis gravida placerat. Aliquam erat volutpat. Ut non diam nulla. Integer felis sapien, faucibus in egestas ut, bibendum non nibh.

Donec vel dapibus erat. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum quam augue, semper sit amet vehicula sit amet, pellentesque pellentesque nisi. Proin vel tellus quam. Ut vehicula massa a sem mollis placerat. In venenatis ligula in arcu egestas ut congue felis rhoncus. Nunc sollicitudin eleifend lacus vel vestibulum. Sed velit urna, condimentum et lobortis id, semper nec metus. Ut mattis tortor id tortor dignissim sodales. Phasellus et varius tellus. Morbi id fermentum lectus. Sed sed malesuada ipsum. Aenean elit nisi, commodo nec gravida posuere, venenatis ac odio. Phasellus malesuada dictum faucibus. Duis vitae urna at massa placerat varius nec a quam. Morbi nec tortor purus, at bibendum nulla.
