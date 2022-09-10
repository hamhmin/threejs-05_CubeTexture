### threejs-05_CubeTexture


CubeTexture 를 이용한 3d공간과 직육면체 거울 만들기

## 배운 내용
- material 
    * Basic
    * Standard
    * Lambert
    * Phong
    * Toon
    * Normal
    * Matcap
    
- material 공통 옵션
    flatshading, side

- MeshStandardMaterial에 효과 더하기
    * map: 베이스 텍스쳐
    * roughness: 빛반사 강도
    * metalness: 금속성 n만큼 부여 
    * normalMap: 선명도 강화
    * roughnessMap: 빛반사 활성도 변환
    * aoMap: 그림자 강화
    * aoMapIntensity: 그림자 강화값

- EnvironmentMap 사용법
- TextureLoader, LoadingManager 사용법
- CubeTextureLoader 사용법
- skybox 응용

- texture filter
    * .magFilter = THREE.NearestFilter

