char __fastcall sub_7FF6743E0CA8(__int64 a1)
{
  char *v1; // rbx
  int v2; // esi
  __int64 v3; // rdi
  __int64 v4; // rax
  char v5; // al
  __int64 v6; // rbx
  char v7; // r10
  _BYTE *v8; // r11
  char v9; // r8
  int v10; // eax
  _BYTE *v11; // rcx
  __int64 v12; // r9
  _BYTE *v13; // rbx
  __int64 v14; // r9
  char v15; // al
  __int64 v16; // r11
  int v17; // er8
  _BYTE *v18; // r10
  char v19; // dl
  unsigned __int64 v20; // rcx
  int v21; // eax
  _BYTE *v22; // rbx
  unsigned int v23; // ecx
  __int64 v24; // r9
  char v25; // al
  char v26; // al
  __int64 v27; // r9
  _BYTE *v28; // rcx
  __int64 v29; // r8
  int v30; // edx
  char v31; // al

  v1 = (char *)(a1 + 0x4A8);
  v2 = 0;
  v3 = a1 + 0x190;
  if ( byte_7FF67AD98D48 )
  {
    switch ( byte_7FF67AD98D48 )
    {
      case 1:
        v22 = (_BYTE *)(a1 + 0x4AE);
        v23 = 0xA87D8528;
        v24 = 0x18i64;
        do
        {
          v25 = v23;
          v23 -= 9;
          LOBYTE(v4) = v22[0xFFFFFCE2] ^ v25;
          *v22++ = v4;
          --v24;
        }
        while ( v24 );
        break;
      case 2:
        v15 = *v1;
        if ( (*v1 & 0x40) == 0 || (*(_BYTE *)(a1 + 0x4A9) & 0x10) == 0 )
        {
          *(_BYTE *)(a1 + 0x4A9) |= 0x10u;
          *v1 = v15 | 0x40;
          *(_QWORD *)(a1 + 0x4B0) = sub_7FF670B1D4F8(0x48i64);
        }
        v16 = *((_QWORD *)v1 + 1);
        v17 = 0xB7F7DDF;
        v18 = (_BYTE *)v3;
        do
        {
          v19 = *v18++ + v17;
          v20 = 0xC * ((v2 & 1u) + 1) - (unsigned __int64)(unsigned int)v2;
          v21 = 0x10 * v2++;
          LODWORD(v4) = ~v21;
          v17 ^= v4;
          *(_BYTE *)(v20 + v16 + 0x18) = v19;
        }
        while ( v2 < 0x18 );
        break;
      case 3:
        v13 = (_BYTE *)(a1 + 0x4AE);
        v14 = 0x18i64;
        do
        {
          LOBYTE(v4) = __ROL1__(v13[0xFFFFFCE2], 4);
          *v13++ = v4;
          --v14;
        }
        while ( v14 );
        break;
      case 4:
        v11 = (_BYTE *)(a1 + 0x190);
        v12 = 0x18i64;
        do
        {
          LOBYTE(v4) = ~(*v11 - v11[0x319]);
          v11[0x31E] = v4;
          ++v11;
          --v12;
        }
        while ( v12 );
        break;
      case 5:
        v5 = *v1;
        if ( (*v1 & 0x40) == 0 || (*(_BYTE *)(a1 + 0x4A9) & 0x10) == 0 )
        {
          *(_BYTE *)(a1 + 0x4A9) |= 0x10u;
          *v1 = v5 | 0x40;
          *(_QWORD *)(a1 + 0x4B0) = sub_7FF670B1D4F8(0x48i64);
        }
        v6 = *((_QWORD *)v1 + 1);
        v7 = 0x35;
        v8 = (_BYTE *)v3;
        do
        {
          v9 = *v8 ^ v7;
          v10 = 0x18;
          if ( v2 % 3u != 1 )
            v10 = 0x30;
          v7 += 0x11;
          ++v8;
          v4 = v2 + v10;
          ++v2;
          *(_BYTE *)(v4 + v6) = v9;
        }
        while ( v2 < 0x18 );
        break;
      default:
        LOBYTE(v4) = sub_7FF6743DF384(v1, v3);
        break;
    }
  }
  else
  {
    v26 = *v1;
    if ( (*v1 & 0x40) == 0 || (*(_BYTE *)(a1 + 0x4A9) & 0x10) == 0 )
    {
      *(_BYTE *)(a1 + 0x4A9) |= 0x10u;
      *v1 = v26 | 0x40;
      *(_QWORD *)(a1 + 0x4B0) = sub_7FF670B1D4F8(0x48i64);
    }
    v27 = 0x18i64;
    v28 = (_BYTE *)(*((_QWORD *)v1 + 1) + 0x18i64);
    v29 = v3 - (_QWORD)v28;
    v30 = 0x192FFE89;
    do
    {
      v31 = v30;
      v30 += v2;
      LOBYTE(v4) = v28[v29] ^ v31;
      v2 += 0x10;
      *v28++ = v4;
      --v27;
    }
    while ( v27 );
  }
  *(_OWORD *)v3 = xmmword_7FF67AB73B90;
  *(_QWORD *)(v3 + 0x10) = qword_7FF67AB73BA0;
  return v4;
}
