``` plantuml
@startuml
title 【親子丼】

start

repeat
    :米を研ぐ;
repeat while (研ぎ汁が白濁)

fork
    :炊飯器をセットする;
fork again
    :玉ねぎの皮を剥く;
    :玉ねぎを薄切りにする;
    :鶏もも肉を一口サイズに切る;
    fork
        repeat
            :フライパンに油をひき, むね肉を中火で炒める;
        repeat while(鶏肉が赤い)
        fork again
            :卵を割る;
            :卵をとく;
            :醤油と砂糖を目分量入れる;
    end fork
    :玉ねぎをフライパンに入れる;
    repeat
        :炒める;
    repeat while(玉ねぎが白い)
    :火を止める;
    :卵をフライパンに流す;
    repeat
    repeat while(卵が生である)
end fork
:ご飯を椀に盛る;
:フライパンの中身をご飯の上にのせる;

stop

@enduml
```